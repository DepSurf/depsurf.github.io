# Function: <code>crng_backtrack_protect</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void crng_backtrack_protect(__u8 * tmp, int used)
```

```json
{
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584512304,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:924",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584512304,
      "name": "crng_backtrack_protect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void crng_backtrack_protect(__u8 * tmp, int used)
```

```json
{
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584694368,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:924",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584694368,
      "name": "crng_backtrack_protect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void crng_backtrack_protect(__u8 * tmp, int used)
```

```json
{
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584776032,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:908",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584776032,
      "name": "crng_backtrack_protect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void crng_backtrack_protect(__u8 * tmp, int used)
```

```json
{
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585196128,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:907",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585196128,
      "name": "crng_backtrack_protect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void crng_backtrack_protect(__u32 * tmp, int used)
```

```json
{
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585431984,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:1016",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585431984,
      "name": "crng_backtrack_protect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void crng_backtrack_protect(__u8 * tmp, int used)
```

```json
{
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585556048,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:1029",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585556048,
      "name": "crng_backtrack_protect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void crng_backtrack_protect(__u8 * tmp, int used)
```

```json
{
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585776528,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:1106",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585776528,
      "name": "crng_backtrack_protect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void crng_backtrack_protect(__u8 * tmp, int used)
```

```json
{
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585919232,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:1106",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585919232,
      "name": "crng_backtrack_protect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586657453,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:1053",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_crng_user"
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
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586767997,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:1053",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_crng_user"
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
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586647277,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:1043",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:extract_crng_user"
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
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587194876,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:1071",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes"
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void crng_backtrack_protect(__u8 * tmp, int used)
```

```json
{
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498740424,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:1106",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498740424,
      "name": "crng_backtrack_protect",
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
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231360376,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:1106",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:get_random_bytes"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void crng_backtrack_protect(__u8 * tmp, int used)
```

```json
{
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291895488,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:1106",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291895488,
      "name": "crng_backtrack_protect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276243084,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:1106",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:get_random_bytes"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void crng_backtrack_protect(__u8 * tmp, int used)
```

```json
{
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585680208,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:1106",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585680208,
      "name": "crng_backtrack_protect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void crng_backtrack_protect(__u8 * tmp, int used)
```

```json
{
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585540080,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:1106",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585540080,
      "name": "crng_backtrack_protect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void crng_backtrack_protect(__u8 * tmp, int used)
```

```json
{
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585869632,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:1106",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585869632,
      "name": "crng_backtrack_protect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void crng_backtrack_protect(__u8 * tmp, int used)
```

```json
{
  "name": "crng_backtrack_protect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585977504,
      "name": "crng_backtrack_protect",
      "external": false,
      "loc": "drivers/char/random.c:1106",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585977504,
      "name": "crng_backtrack_protect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void crng_backtrack_protect(__u8 * tmp, int used)
```
</details>
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>__u8 * tmp</code> ➡️ <code>__u32 * tmp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>__u32 * tmp</code> ➡️ <code>__u8 * tmp</code>
</li>
</ul>
</details>
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
void crng_backtrack_protect(__u8 * tmp, int used)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void crng_backtrack_protect(__u8 * tmp, int used)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void crng_backtrack_protect(__u8 * tmp, int used)
```
</details>
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
