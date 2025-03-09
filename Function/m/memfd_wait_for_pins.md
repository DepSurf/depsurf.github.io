# Function: <code>memfd_wait_for_pins</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581548960,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:73",
      "file": "mm/memfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memfd.c:memfd_fcntl"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581634142,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:65",
      "file": "mm/memfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memfd.c:memfd_fcntl"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int memfd_wait_for_pins(struct address_space * mapping)
```

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749936,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:65",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749936,
      "name": "memfd_wait_for_pins",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1024
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
int memfd_wait_for_pins(struct address_space * mapping)
```

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581822016,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:66",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581822016,
      "name": "memfd_wait_for_pins",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1150
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
int memfd_wait_for_pins(struct address_space * mapping)
```

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582039840,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:66",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582039840,
      "name": "memfd_wait_for_pins",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 739
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
int memfd_wait_for_pins(struct address_space * mapping)
```

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582088672,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:66",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582088672,
      "name": "memfd_wait_for_pins",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 739
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
int memfd_wait_for_pins(struct address_space * mapping)
```

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582113744,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:66",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582113744,
      "name": "memfd_wait_for_pins",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 750
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
int memfd_wait_for_pins(struct address_space * mapping)
```

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582430128,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:74",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582430128,
      "name": "memfd_wait_for_pins",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 731
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
int memfd_wait_for_pins(struct address_space * mapping)
```

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582946368,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:74",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582946368,
      "name": "memfd_wait_for_pins",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 919
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
int memfd_wait_for_pins(struct address_space * mapping)
```

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583503392,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:74",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583503392,
      "name": "memfd_wait_for_pins",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 966
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
int memfd_wait_for_pins(struct address_space * mapping)
```

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:75",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583717696,
      "name": "memfd_wait_for_pins",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 945
    },
    {
      "addr": 18446744071596572550,
      "name": "memfd_wait_for_pins.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int memfd_wait_for_pins(struct address_space * mapping)
```

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:75",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583918320,
      "name": "memfd_wait_for_pins",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 926
    },
    {
      "addr": 18446744071597477061,
      "name": "memfd_wait_for_pins.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int memfd_wait_for_pins(struct address_space * mapping)
```

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493284328,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:66",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493284328,
      "name": "memfd_wait_for_pins",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1360
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
int memfd_wait_for_pins(struct address_space * mapping)
```

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226888568,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:66",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226888568,
      "name": "memfd_wait_for_pins",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1080
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
int memfd_wait_for_pins(struct address_space * mapping)
```

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286820832,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:66",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286820832,
      "name": "memfd_wait_for_pins",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1644
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
int memfd_wait_for_pins(struct address_space * mapping)
```

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273032070,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:66",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273032070,
      "name": "memfd_wait_for_pins",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1250
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
int memfd_wait_for_pins(struct address_space * mapping)
```

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581790752,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:66",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790752,
      "name": "memfd_wait_for_pins",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1150
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
int memfd_wait_for_pins(struct address_space * mapping)
```

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581728432,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:66",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581728432,
      "name": "memfd_wait_for_pins",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1126
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
int memfd_wait_for_pins(struct address_space * mapping)
```

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581782064,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:66",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581782064,
      "name": "memfd_wait_for_pins",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1150
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
int memfd_wait_for_pins(struct address_space * mapping)
```

```json
{
  "name": "memfd_wait_for_pins",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581851088,
      "name": "memfd_wait_for_pins",
      "external": false,
      "loc": "mm/memfd.c:66",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581851088,
      "name": "memfd_wait_for_pins",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
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
int memfd_wait_for_pins(struct address_space * mapping)
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
