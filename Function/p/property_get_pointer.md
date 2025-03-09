# Function: <code>property_get_pointer</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
const void * property_get_pointer(const struct property_entry * prop)
```

```json
{
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585698160,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/property.c:59",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:property_entries_dup",
        "drivers/base/property.c:property_entry_free_data",
        "drivers/base/property.c:pset_prop_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585698160,
      "name": "property_get_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
const void * property_get_pointer(const struct property_entry * prop)
```

```json
{
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585833120,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:106",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:property_entries_dup",
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585833120,
      "name": "property_get_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
const void * property_get_pointer(const struct property_entry * prop)
```

```json
{
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586069152,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:145",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586069152,
      "name": "property_get_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
const void * property_get_pointer(const struct property_entry * prop)
```

```json
{
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586217104,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:145",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586217104,
      "name": "property_get_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586982629,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:106",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:property_entry_copy_data",
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_find"
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
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587068149,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:106",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:property_entry_copy_data",
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_find"
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
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586954628,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:120",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:property_entry_copy_data",
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_read_int_array"
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
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587521460,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:122",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:property_entry_copy_data",
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_read_int_array"
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
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588848887,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:122",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:property_entry_copy_data",
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_read_int_array"
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
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590351333,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:122",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:property_entry_copy_data",
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_read_string_array",
        "drivers/base/swnode.c:property_entry_read_int_array"
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
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590672213,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:122",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:property_entry_copy_data",
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_read_string_array",
        "drivers/base/swnode.c:property_entry_read_int_array"
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
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591033573,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:122",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:property_entry_copy_data",
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_read_string_array",
        "drivers/base/swnode.c:property_entry_read_int_array"
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
const void * property_get_pointer(const struct property_entry * prop)
```

```json
{
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499025520,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:145",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499025520,
      "name": "property_get_pointer",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
const void * property_get_pointer(const struct property_entry * prop)
```

```json
{
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231587012,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:145",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231587012,
      "name": "property_get_pointer",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
const void * property_get_pointer(const struct property_entry * prop)
```

```json
{
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292191008,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:145",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292191008,
      "name": "property_get_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
const void * property_get_pointer(const struct property_entry * prop)
```

```json
{
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276392180,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:145",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276392180,
      "name": "property_get_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
const void * property_get_pointer(const struct property_entry * prop)
```

```json
{
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585977312,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:145",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585977312,
      "name": "property_get_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
const void * property_get_pointer(const struct property_entry * prop)
```

```json
{
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585826576,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:145",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826576,
      "name": "property_get_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
const void * property_get_pointer(const struct property_entry * prop)
```

```json
{
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586167120,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:145",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586167120,
      "name": "property_get_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
const void * property_get_pointer(const struct property_entry * prop)
```

```json
{
  "name": "property_get_pointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586276048,
      "name": "property_get_pointer",
      "external": false,
      "loc": "drivers/base/swnode.c:145",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:property_entry_free_data",
        "drivers/base/swnode.c:property_entry_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586276048,
      "name": "property_get_pointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
const void * property_get_pointer(const struct property_entry * prop)
```
</details>
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
const void * property_get_pointer(const struct property_entry * prop)
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
