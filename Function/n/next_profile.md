# Function: <code>next_profile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582470263,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:892",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582692695,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1386",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582786340,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1492",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct aa_profile * next_profile(struct aa_ns * root, struct aa_profile * profile)
```

```json
{
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582879760,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2014",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582879760,
      "name": "next_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
struct aa_profile * next_profile(struct aa_ns * root, struct aa_profile * profile)
```

```json
{
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583035520,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2078",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583035520,
      "name": "next_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
struct aa_profile * next_profile(struct aa_ns * root, struct aa_profile * profile)
```

```json
{
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583236112,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2075",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236112,
      "name": "next_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
struct aa_profile * next_profile(struct aa_ns * root, struct aa_profile * profile)
```

```json
{
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583353696,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2073",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353696,
      "name": "next_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
struct aa_profile * next_profile(struct aa_ns * root, struct aa_profile * profile)
```

```json
{
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583541712,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2078",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583541712,
      "name": "next_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
struct aa_profile * next_profile(struct aa_ns * root, struct aa_profile * profile)
```

```json
{
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583647440,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2046",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583647440,
      "name": "next_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584005882,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2165",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
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
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584125658,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2162",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
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
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584152842,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2163",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
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
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584536986,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2163",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
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
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585177674,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2183",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
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
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585906890,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2372",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
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
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586139050,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2420",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
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
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586388218,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2418",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_next",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct aa_profile * next_profile(struct aa_ns * root, struct aa_profile * profile)
```

```json
{
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495439416,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2046",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495439416,
      "name": "next_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
struct aa_profile * next_profile(struct aa_ns * root, struct aa_profile * profile)
```

```json
{
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228807028,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2046",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228807028,
      "name": "next_profile",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct aa_profile * next_profile(struct aa_ns * root, struct aa_profile * profile)
```

```json
{
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289483888,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2046",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289483888,
      "name": "next_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
struct aa_profile * next_profile(struct aa_ns * root, struct aa_profile * profile)
```

```json
{
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274633652,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2046",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274633652,
      "name": "next_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
struct aa_profile * next_profile(struct aa_ns * root, struct aa_profile * profile)
```

```json
{
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583616176,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2046",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583616176,
      "name": "next_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
struct aa_profile * next_profile(struct aa_ns * root, struct aa_profile * profile)
```

```json
{
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583553232,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2046",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583553232,
      "name": "next_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
struct aa_profile * next_profile(struct aa_ns * root, struct aa_profile * profile)
```

```json
{
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583599952,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2046",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583599952,
      "name": "next_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
struct aa_profile * next_profile(struct aa_ns * root, struct aa_profile * profile)
```

```json
{
  "name": "next_profile",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583697040,
      "name": "next_profile",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2046",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:p_next",
        "security/apparmor/apparmorfs.c:p_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583697040,
      "name": "next_profile",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
struct aa_profile * next_profile(struct aa_ns * root, struct aa_profile * profile)
```
</details>
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
struct aa_profile * next_profile(struct aa_ns * root, struct aa_profile * profile)
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
