# Function: <code>property_entry_read_int_array</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585833768,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:224",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_read_int_array"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586069798,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:263",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_read_int_array"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586217750,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:263",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_read_int_array"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int property_entry_read_int_array(const struct property_entry * props, const char * name, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586984592,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:144",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586984592,
      "name": "property_entry_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int property_entry_read_int_array(const struct property_entry * props, const char * name, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587070384,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:144",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587070384,
      "name": "property_entry_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int property_entry_read_int_array(const struct property_entry * props, const char * name, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586954064,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:158",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586954064,
      "name": "property_entry_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int property_entry_read_int_array(const struct property_entry * props, const char * name, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:160",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587520032,
      "name": "property_entry_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
    },
    {
      "addr": 18446744071592490103,
      "name": "property_entry_read_int_array.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int property_entry_read_int_array(const struct property_entry * props, const char * name, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:160",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588848080,
      "name": "property_entry_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071594359773,
      "name": "property_entry_read_int_array.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int property_entry_read_int_array(const struct property_entry * props, const char * name, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:160",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590352288,
      "name": "property_entry_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071596247109,
      "name": "property_entry_read_int_array.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int property_entry_read_int_array(const struct property_entry * props, const char * name, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:160",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590673232,
      "name": "property_entry_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071596775511,
      "name": "property_entry_read_int_array.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int property_entry_read_int_array(const struct property_entry * props, const char * name, unsigned int elem_size, void * val, size_t nval)
```

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:160",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591034592,
      "name": "property_entry_read_int_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071597684761,
      "name": "property_entry_read_int_array.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499026364,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:263",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_read_int_array"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231587744,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:263",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_read_int_array"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292192700,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:263",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_read_int_array"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276392870,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:263",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_read_int_array"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585977958,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:263",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_read_int_array"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585827222,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:263",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_read_int_array"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586167766,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:263",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_read_int_array"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "property_entry_read_int_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586276694,
      "name": "property_entry_read_int_array",
      "external": false,
      "loc": "drivers/base/swnode.c:263",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_read_int_array"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int property_entry_read_int_array(const struct property_entry * props, const char * name, unsigned int elem_size, void * val, size_t nval)
```
</details>
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
