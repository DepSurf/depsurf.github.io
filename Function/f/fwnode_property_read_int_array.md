# Function: <code>fwnode_property_read_int_array</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int fwnode_property_read_int_array(struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585030464,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:434",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585030464,
      "name": "fwnode_property_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585453216,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:443",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585453216,
      "name": "fwnode_property_read_int_array",
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
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585695488,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:504",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:fwnode_get_mac_addr",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585695488,
      "name": "fwnode_property_read_int_array",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585825776,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:229",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:fwnode_get_mac_addr",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585825776,
      "name": "fwnode_property_read_int_array",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586061296,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:229",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:fwnode_get_mac_addr",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586061296,
      "name": "fwnode_property_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586209184,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:229",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:fwnode_get_mac_addr",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586209184,
      "name": "fwnode_property_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586972768,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:229",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586972768,
      "name": "fwnode_property_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587058464,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:229",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587058464,
      "name": "fwnode_property_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586942304,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:229",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586942304,
      "name": "fwnode_property_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587506624,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:229",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587506624,
      "name": "fwnode_property_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588831680,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:245",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588831680,
      "name": "fwnode_property_read_int_array",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590332304,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:252",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590332304,
      "name": "fwnode_property_read_int_array",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590652320,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:256",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590652320,
      "name": "fwnode_property_read_int_array",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591012464,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:256",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591012464,
      "name": "fwnode_property_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499013976,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:229",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:fwnode_get_mac_addr",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499013976,
      "name": "fwnode_property_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231577588,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:229",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:fwnode_get_mac_addr",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231577588,
      "name": "fwnode_property_read_int_array",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292176000,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:229",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292176000,
      "name": "fwnode_property_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276382890,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:229",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276382890,
      "name": "fwnode_property_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585969392,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:229",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:fwnode_get_mac_addr",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585969392,
      "name": "fwnode_property_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585818656,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:229",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:fwnode_get_mac_addr",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585818656,
      "name": "fwnode_property_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586159200,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:229",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:fwnode_get_mac_addr",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586159200,
      "name": "fwnode_property_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int fwnode_property_read_int_array(const struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586267904,
      "name": "fwnode_property_read_int_array",
      "external": false,
      "loc": "drivers/base/property.c:229",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:fwnode_get_mac_addr",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586267904,
      "name": "fwnode_property_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int fwnode_property_read_int_array(struct fwnode_handle * fwnode, const char * propname, unsigned int elem_size, void * val, size_t nval)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle * fwnode</code> ➡️ <code>const struct fwnode_handle * fwnode</code>
</li>
</ul>
</details>
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
