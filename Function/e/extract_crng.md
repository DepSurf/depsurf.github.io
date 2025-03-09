# Function: <code>extract_crng</code>

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
void extract_crng(__u8 * out)
```

```json
{
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584507248,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:887",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:_crng_backtrack_protect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584507248,
      "name": "extract_crng",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void extract_crng(__u8 * out)
```

```json
{
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584689360,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:887",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:get_random_bytes",
        "drivers/char/random.c:_crng_backtrack_protect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584689360,
      "name": "extract_crng",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void extract_crng(__u8 * out)
```

```json
{
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584775824,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:871",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_crng_backtrack_protect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584775824,
      "name": "extract_crng",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void extract_crng(__u8 * out)
```

```json
{
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585195920,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:870",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_crng_backtrack_protect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585195920,
      "name": "extract_crng",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void extract_crng(__u32 * out)
```

```json
{
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585431792,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:979",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_crng_backtrack_protect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585431792,
      "name": "extract_crng",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void extract_crng(__u8 * out)
```

```json
{
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585555856,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:992",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_crng_backtrack_protect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585555856,
      "name": "extract_crng",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void extract_crng(__u8 * out)
```

```json
{
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585771424,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:1069",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_crng_backtrack_protect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585771424,
      "name": "extract_crng",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void extract_crng(__u8 * out)
```

```json
{
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585914064,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:1069",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_crng_backtrack_protect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585914064,
      "name": "extract_crng",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586653629,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:1016",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:_get_random_bytes",
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
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586764333,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:1016",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:_get_random_bytes",
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
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586645470,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:1006",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:_get_random_bytes",
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
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587192950,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:1042",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:_get_random_bytes",
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
void extract_crng(__u8 * out)
```

```json
{
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498740040,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:1069",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_crng_backtrack_protect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498740040,
      "name": "extract_crng",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231360936,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:1069",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
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
void extract_crng(__u8 * out)
```

```json
{
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291895168,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:1069",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_crng_backtrack_protect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291895168,
      "name": "extract_crng",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276243590,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:1069",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
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
void extract_crng(__u8 * out)
```

```json
{
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585675072,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:1069",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_crng_backtrack_protect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585675072,
      "name": "extract_crng",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void extract_crng(__u8 * out)
```

```json
{
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585534912,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:1069",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_crng_backtrack_protect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585534912,
      "name": "extract_crng",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void extract_crng(__u8 * out)
```

```json
{
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585864464,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:1069",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_crng_backtrack_protect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585864464,
      "name": "extract_crng",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void extract_crng(__u8 * out)
```

```json
{
  "name": "extract_crng",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585972144,
      "name": "extract_crng",
      "external": false,
      "loc": "drivers/char/random.c:1069",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_crng_backtrack_protect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585972144,
      "name": "extract_crng",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void extract_crng(__u8 * out)
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
<code>__u8 * out</code> ➡️ <code>__u32 * out</code>
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
<code>__u32 * out</code> ➡️ <code>__u8 * out</code>
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
void extract_crng(__u8 * out)
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
void extract_crng(__u8 * out)
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
void extract_crng(__u8 * out)
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
