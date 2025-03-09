# Function: <code>__next_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct aa_ns * __next_ns(struct aa_ns * root, struct aa_ns * ns)
```

```json
{
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582468864,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:792",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__first_profile",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582468864,
      "name": "__next_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
struct aa_ns * __next_ns(struct aa_ns * root, struct aa_ns * ns)
```

```json
{
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582691056,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1286",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__first_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582691056,
      "name": "__next_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
struct aa_ns * __next_ns(struct aa_ns * root, struct aa_ns * ns)
```

```json
{
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582784112,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1392",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:__first_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582784112,
      "name": "__next_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
struct aa_ns * __next_ns(struct aa_ns * root, struct aa_ns * ns)
```

```json
{
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582879600,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1913",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:next_profile",
        "security/apparmor/apparmorfs.c:next_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582879600,
      "name": "__next_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
struct aa_ns * __next_ns(struct aa_ns * root, struct aa_ns * ns)
```

```json
{
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583035360,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1977",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:next_profile",
        "security/apparmor/apparmorfs.c:next_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583035360,
      "name": "__next_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
struct aa_ns * __next_ns(struct aa_ns * root, struct aa_ns * ns)
```

```json
{
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583235952,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1974",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:next_profile",
        "security/apparmor/apparmorfs.c:next_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583235952,
      "name": "__next_ns",
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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct aa_ns * __next_ns(struct aa_ns * root, struct aa_ns * ns)
```

```json
{
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583353536,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1972",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:next_profile",
        "security/apparmor/apparmorfs.c:next_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353536,
      "name": "__next_ns",
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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct aa_ns * __next_ns(struct aa_ns * root, struct aa_ns * ns)
```

```json
{
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583541552,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1977",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:next_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583541552,
      "name": "__next_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
struct aa_ns * __next_ns(struct aa_ns * root, struct aa_ns * ns)
```

```json
{
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583647280,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1945",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:next_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583647280,
      "name": "__next_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584005966,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2064",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start"
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
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584125742,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2061",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start"
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
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584152938,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2062",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start"
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
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584537082,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2062",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start"
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
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585177782,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2082",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start"
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
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585906998,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2271",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start"
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
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586139158,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2319",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start"
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
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586388326,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2317",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:p_start"
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
struct aa_ns * __next_ns(struct aa_ns * root, struct aa_ns * ns)
```

```json
{
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495439216,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1945",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:next_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495439216,
      "name": "__next_ns",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct aa_ns * __next_ns(struct aa_ns * root, struct aa_ns * ns)
```

```json
{
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228806868,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1945",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:next_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228806868,
      "name": "__next_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
struct aa_ns * __next_ns(struct aa_ns * root, struct aa_ns * ns)
```

```json
{
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289483600,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1945",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:next_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289483600,
      "name": "__next_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
struct aa_ns * __next_ns(struct aa_ns * root, struct aa_ns * ns)
```

```json
{
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274633480,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1945",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:next_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274633480,
      "name": "__next_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
struct aa_ns * __next_ns(struct aa_ns * root, struct aa_ns * ns)
```

```json
{
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583616016,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1945",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:next_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583616016,
      "name": "__next_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
struct aa_ns * __next_ns(struct aa_ns * root, struct aa_ns * ns)
```

```json
{
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583553072,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1945",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:next_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583553072,
      "name": "__next_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
struct aa_ns * __next_ns(struct aa_ns * root, struct aa_ns * ns)
```

```json
{
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583599792,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1945",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:next_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583599792,
      "name": "__next_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
struct aa_ns * __next_ns(struct aa_ns * root, struct aa_ns * ns)
```

```json
{
  "name": "__next_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583696880,
      "name": "__next_ns",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1945",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:next_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583696880,
      "name": "__next_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct aa_ns * __next_ns(struct aa_ns * root, struct aa_ns * ns)
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
