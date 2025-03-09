# Function: <code>fwnode_find_reference</code>

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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
```

```json
{
  "name": "fwnode_find_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586060256,
      "name": "fwnode_find_reference",
      "external": true,
      "loc": "drivers/base/property.c:498",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:device_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060256,
      "name": "fwnode_find_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
```

```json
{
  "name": "fwnode_find_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586208144,
      "name": "fwnode_find_reference",
      "external": true,
      "loc": "drivers/base/property.c:498",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586208144,
      "name": "fwnode_find_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
```

```json
{
  "name": "fwnode_find_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586974528,
      "name": "fwnode_find_reference",
      "external": true,
      "loc": "drivers/base/property.c:498",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586974528,
      "name": "fwnode_find_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
```

```json
{
  "name": "fwnode_find_reference",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587063249,
      "name": "fwnode_find_reference",
      "external": true,
      "loc": "drivers/base/property.c:498",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_connection_find_match"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587060192,
      "name": "fwnode_find_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
```

```json
{
  "name": "fwnode_find_reference",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586947257,
      "name": "fwnode_find_reference",
      "external": true,
      "loc": "drivers/base/property.c:498",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_connection_find_match"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586943984,
      "name": "fwnode_find_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
```

```json
{
  "name": "fwnode_find_reference",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587511682,
      "name": "fwnode_find_reference",
      "external": true,
      "loc": "drivers/base/property.c:498",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_connection_find_match"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587508304,
      "name": "fwnode_find_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
```

```json
{
  "name": "fwnode_find_reference",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588835222,
      "name": "fwnode_find_reference",
      "external": true,
      "loc": "drivers/base/property.c:545",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_devcon_matches"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588832976,
      "name": "fwnode_find_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
```

```json
{
  "name": "fwnode_find_reference",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590336470,
      "name": "fwnode_find_reference",
      "external": true,
      "loc": "drivers/base/property.c:553",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_devcon_matches"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590333824,
      "name": "fwnode_find_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
```

```json
{
  "name": "fwnode_find_reference",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590656518,
      "name": "fwnode_find_reference",
      "external": true,
      "loc": "drivers/base/property.c:560",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_devcon_matches"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590653840,
      "name": "fwnode_find_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
```

```json
{
  "name": "fwnode_find_reference",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591017046,
      "name": "fwnode_find_reference",
      "external": true,
      "loc": "drivers/base/property.c:596",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_devcon_matches"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591013984,
      "name": "fwnode_find_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
```

```json
{
  "name": "fwnode_find_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499012488,
      "name": "fwnode_find_reference",
      "external": true,
      "loc": "drivers/base/property.c:498",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499012488,
      "name": "fwnode_find_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
```

```json
{
  "name": "fwnode_find_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231576020,
      "name": "fwnode_find_reference",
      "external": true,
      "loc": "drivers/base/property.c:498",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231576020,
      "name": "fwnode_find_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
```

```json
{
  "name": "fwnode_find_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292173440,
      "name": "fwnode_find_reference",
      "external": true,
      "loc": "drivers/base/property.c:498",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292173440,
      "name": "fwnode_find_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
```

```json
{
  "name": "fwnode_find_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276381582,
      "name": "fwnode_find_reference",
      "external": true,
      "loc": "drivers/base/property.c:498",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276381582,
      "name": "fwnode_find_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
```

```json
{
  "name": "fwnode_find_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585968352,
      "name": "fwnode_find_reference",
      "external": true,
      "loc": "drivers/base/property.c:498",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585968352,
      "name": "fwnode_find_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
```

```json
{
  "name": "fwnode_find_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585817616,
      "name": "fwnode_find_reference",
      "external": true,
      "loc": "drivers/base/property.c:498",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585817616,
      "name": "fwnode_find_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
```

```json
{
  "name": "fwnode_find_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586158160,
      "name": "fwnode_find_reference",
      "external": true,
      "loc": "drivers/base/property.c:498",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586158160,
      "name": "fwnode_find_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
```

```json
{
  "name": "fwnode_find_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586266864,
      "name": "fwnode_find_reference",
      "external": true,
      "loc": "drivers/base/property.c:498",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586266864,
      "name": "fwnode_find_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct fwnode_handle * fwnode_find_reference(const struct fwnode_handle * fwnode, const char * name, unsigned int index)
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
