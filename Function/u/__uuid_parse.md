# Function: <code>__uuid_parse</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __uuid_parse(const char * uuid, __u8 * b, const u8 * ei)
```

```json
{
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583449984,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:103",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583449984,
      "name": "__uuid_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __uuid_parse(const char * uuid, __u8 * b, const u8 * ei)
```

```json
{
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583630080,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:103",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583630080,
      "name": "__uuid_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583846800,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:103",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583846640,
      "name": "__uuid_parse.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583930512,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:103",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583930352,
      "name": "__uuid_parse.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584110080,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:95",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584109904,
      "name": "__uuid_parse.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584232928,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:95",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584232752,
      "name": "__uuid_parse.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584639904,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:105",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584639664,
      "name": "__uuid_parse.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584759444,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:105",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584759200,
      "name": "__uuid_parse.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584787876,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:105",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584787632,
      "name": "__uuid_parse.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585218692,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:105",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585218400,
      "name": "__uuid_parse.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586056551,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:105",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586056208,
      "name": "__uuid_parse.part.0",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587040525,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:105",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587040144,
      "name": "__uuid_parse.part.0",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587297645,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:105",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587297264,
      "name": "__uuid_parse.part.0",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587583469,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:105",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587583088,
      "name": "__uuid_parse.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496108568,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:95",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496108352,
      "name": "__uuid_parse.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229433688,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:95",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229433512,
      "name": "__uuid_parse.part.0",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290356972,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:95",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290356608,
      "name": "__uuid_parse.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275174050,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:95",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275173862,
      "name": "__uuid_parse.part.0",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584201664,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:95",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584201488,
      "name": "__uuid_parse.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584136880,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:95",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584136704,
      "name": "__uuid_parse.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584185424,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:95",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584185248,
      "name": "__uuid_parse.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
  "name": "__uuid_parse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584289776,
      "name": "__uuid_parse",
      "external": false,
      "loc": "lib/uuid.c:95",
      "file": "lib/uuid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ],
      "caller_func": [
        "lib/uuid.c:uuid_parse",
        "lib/uuid.c:guid_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289600,
      "name": "__uuid_parse.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int __uuid_parse(const char * uuid, __u8 * b, const u8 * ei)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int __uuid_parse(const char * uuid, __u8 * b, const u8 * ei)
```
</details>
</li>
</ul>
