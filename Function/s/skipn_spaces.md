# Function: <code>skipn_spaces</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582483301,
      "name": "skipn_spaces",
      "external": false,
      "loc": "security/apparmor/lib.c:79",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582716305,
      "name": "skipn_spaces",
      "external": false,
      "loc": "security/apparmor/lib.c:79",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582810961,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:79",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:fqlookupn_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582810736,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582899009,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:78",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:fqlookupn_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582898784,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583057121,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:78",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:fqlookupn_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583056896,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583258033,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:78",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:fqlookupn_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583257808,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583375793,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:78",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:fqlookupn_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583375552,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583562672,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:74",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:fqlookupn_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583562432,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583668400,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:74",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:fqlookupn_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583668160,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584030591,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:74",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584030384,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584149887,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:74",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584149680,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584177048,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:74",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584176800,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584562072,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:74",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584561824,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585207412,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:93",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585207184,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585939684,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:185",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585939440,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586172084,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:185",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586171840,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586423316,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:187",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:aa_label_strn_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586423072,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495461972,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:74",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:fqlookupn_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495461704,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228828944,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:74",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:fqlookupn_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228828496,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289514212,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:74",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:fqlookupn_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289513904,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274649916,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:74",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:fqlookupn_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274649700,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583637136,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:74",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:fqlookupn_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583636896,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583574192,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:74",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:fqlookupn_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583573952,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583620912,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:74",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:fqlookupn_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583620672,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
const char * skipn_spaces(const char * str, size_t n)
```

```json
{
  "name": "skipn_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583718976,
      "name": "skipn_spaces",
      "external": true,
      "loc": "security/apparmor/lib.c:74",
      "file": "security/apparmor/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/apparmor/lib.c:aa_splitn_fqname"
      ],
      "caller_func": [
        "security/apparmor/label.c:aa_label_strn_parse",
        "security/apparmor/label.c:fqlookupn_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718736,
      "name": "skipn_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
const char * skipn_spaces(const char * str, size_t n)
```
</details>
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
