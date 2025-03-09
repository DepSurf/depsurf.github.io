# Function: <code>field_has_hist_vars</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool field_has_hist_vars(struct hist_field * hist_field, unsigned int level)
```

```json
{
  "name": "field_has_hist_vars",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580532912,
      "name": "field_has_hist_vars",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1377",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:field_has_hist_vars",
        "kernel/trace/trace_events_hist.c:field_has_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580532912,
      "name": "field_has_hist_vars",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
bool field_has_hist_vars(struct hist_field * hist_field, unsigned int level)
```

```json
{
  "name": "field_has_hist_vars",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580591024,
      "name": "field_has_hist_vars",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1461",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:field_has_hist_vars",
        "kernel/trace/trace_events_hist.c:field_has_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580591024,
      "name": "field_has_hist_vars",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "field_has_hist_vars",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580678236,
      "name": "field_has_hist_vars",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1615",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580654192,
      "name": "field_has_hist_vars.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "field_has_hist_vars",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580725420,
      "name": "field_has_hist_vars",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1689",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580700736,
      "name": "field_has_hist_vars.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
bool field_has_hist_vars(struct hist_field * hist_field, unsigned int level)
```

```json
{
  "name": "field_has_hist_vars",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580839864,
      "name": "field_has_hist_vars",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:780",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_key_field",
        "kernel/trace/trace_events_hist.c:create_key_field"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_key_field",
        "kernel/trace/trace_events_hist.c:create_key_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580819184,
      "name": "field_has_hist_vars",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
bool field_has_hist_vars(struct hist_field * hist_field, unsigned int level)
```

```json
{
  "name": "field_has_hist_vars",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580830072,
      "name": "field_has_hist_vars",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:783",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_key_field",
        "kernel/trace/trace_events_hist.c:create_key_field"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_key_field",
        "kernel/trace/trace_events_hist.c:create_key_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580810000,
      "name": "field_has_hist_vars",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
bool field_has_hist_vars(struct hist_field * hist_field, unsigned int level)
```

```json
{
  "name": "field_has_hist_vars",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580835672,
      "name": "field_has_hist_vars",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:799",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_key_field",
        "kernel/trace/trace_events_hist.c:create_key_field"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_key_field",
        "kernel/trace/trace_events_hist.c:create_key_field"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580814368,
      "name": "field_has_hist_vars",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
bool field_has_hist_vars(struct hist_field * hist_field, unsigned int level)
```

```json
{
  "name": "field_has_hist_vars",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581035934,
      "name": "field_has_hist_vars",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:823",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581010224,
      "name": "field_has_hist_vars",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
bool field_has_hist_vars(struct hist_field * hist_field, unsigned int level)
```

```json
{
  "name": "field_has_hist_vars",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581290673,
      "name": "field_has_hist_vars",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:997",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:field_has_hist_vars",
        "kernel/trace/trace_events_hist.c:field_has_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581250448,
      "name": "field_has_hist_vars",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool field_has_hist_vars(struct hist_field * hist_field, unsigned int level)
```

```json
{
  "name": "field_has_hist_vars",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581615431,
      "name": "field_has_hist_vars",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1030",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:field_has_hist_vars",
        "kernel/trace/trace_events_hist.c:field_has_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572000,
      "name": "field_has_hist_vars",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool field_has_hist_vars(struct hist_field * hist_field, unsigned int level)
```

```json
{
  "name": "field_has_hist_vars",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581738010,
      "name": "field_has_hist_vars",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1027",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:field_has_hist_vars",
        "kernel/trace/trace_events_hist.c:field_has_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581691984,
      "name": "field_has_hist_vars",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool field_has_hist_vars(struct hist_field * hist_field, unsigned int level)
```

```json
{
  "name": "field_has_hist_vars",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581854744,
      "name": "field_has_hist_vars",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1020",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields",
        "kernel/trace/trace_events_hist.c:create_key_fields"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:field_has_hist_vars",
        "kernel/trace/trace_events_hist.c:field_has_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581808288,
      "name": "field_has_hist_vars",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
  "name": "field_has_hist_vars",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492033124,
      "name": "field_has_hist_vars",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1689",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492011040,
      "name": "field_has_hist_vars.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "field_has_hist_vars",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285200056,
      "name": "field_has_hist_vars",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1689",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285148784,
      "name": "field_has_hist_vars.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "field_has_hist_vars",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580694220,
      "name": "field_has_hist_vars",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1689",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669536,
      "name": "field_has_hist_vars.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "field_has_hist_vars",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580640428,
      "name": "field_has_hist_vars",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1689",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580615744,
      "name": "field_has_hist_vars.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "field_has_hist_vars",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580685468,
      "name": "field_has_hist_vars",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1689",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660784,
      "name": "field_has_hist_vars.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "field_has_hist_vars",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580742972,
      "name": "field_has_hist_vars",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1689",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_hist_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580718288,
      "name": "field_has_hist_vars.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
bool field_has_hist_vars(struct hist_field * hist_field, unsigned int level)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
bool field_has_hist_vars(struct hist_field * hist_field, unsigned int level)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool field_has_hist_vars(struct hist_field * hist_field, unsigned int level)
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
