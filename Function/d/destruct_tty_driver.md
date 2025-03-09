# Function: <code>destruct_tty_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583957136,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3426",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583957136,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584291008,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3422",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584291008,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584473088,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3422",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584473088,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584558980,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:2980",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_driver_kref_put"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584969472,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3087",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584969472,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585202864,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3108",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585202864,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585321136,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3263",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585321136,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585533200,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3267",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585533200,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585674080,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3263",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585674080,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586398784,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3266",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586398784,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586513808,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3359",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586513808,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586398736,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3408",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586398736,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586925424,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3408",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586925424,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588219280,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3375",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588219280,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589628752,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3372",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589628752,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589932448,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3378",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589932448,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590270960,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3395",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_lookup_driver",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590270960,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498346356,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3263",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_driver_kref_put"
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
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231037844,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3263",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_driver_kref_put"
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
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291534032,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3263",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_driver_kref_put"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276028862,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3263",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276028862,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585435104,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3263",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585435104,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585305152,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3263",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585305152,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585624480,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3263",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585624480,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void destruct_tty_driver(struct kref * kref)
```

```json
{
  "name": "destruct_tty_driver",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585732800,
      "name": "destruct_tty_driver",
      "external": false,
      "loc": "drivers/tty/tty_io.c:3263",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:put_tty_driver",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_one_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585732800,
      "name": "destruct_tty_driver",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void destruct_tty_driver(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void destruct_tty_driver(struct kref * kref)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void destruct_tty_driver(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void destruct_tty_driver(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void destruct_tty_driver(struct kref * kref)
```
</details>
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
