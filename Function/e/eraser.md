# Function: <code>eraser</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583984403,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:975",
      "file": "drivers/tty/n_tty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
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
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584316388,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:949",
      "file": "drivers/tty/n_tty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
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
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584498436,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:949",
      "file": "drivers/tty/n_tty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584576648,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:949",
      "file": "drivers/tty/n_tty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584988680,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:947",
      "file": "drivers/tty/n_tty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585222729,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:964",
      "file": "drivers/tty/n_tty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
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
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585341721,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:977",
      "file": "drivers/tty/n_tty.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
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
void eraser(unsigned char c, struct tty_struct * tty)
```

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585552944,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:979",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585552944,
      "name": "eraser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1272
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
void eraser(unsigned char c, struct tty_struct * tty)
```

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585693824,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:979",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585693824,
      "name": "eraser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1272
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
void eraser(unsigned char c, struct tty_struct * tty)
```

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586422224,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:979",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586422224,
      "name": "eraser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1205
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
void eraser(unsigned char c, struct tty_struct * tty)
```

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586539728,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:975",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586539728,
      "name": "eraser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1205
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
void eraser(unsigned char c, struct tty_struct * tty)
```

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586425264,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:976",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586425264,
      "name": "eraser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1210
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
void eraser(unsigned char c, struct tty_struct * tty)
```

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586951376,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:976",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586951376,
      "name": "eraser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1210
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
void eraser(unsigned char c, struct tty_struct * tty)
```

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588248080,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:953",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588248080,
      "name": "eraser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1266
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
void eraser(unsigned char c, struct tty_struct * tty)
```

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589660560,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:958",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589660560,
      "name": "eraser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1266
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
void eraser(unsigned char c, struct tty_struct * tty)
```

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589964480,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:957",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589964480,
      "name": "eraser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1191
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
void eraser(u8 c, const struct tty_struct * tty)
```

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590303280,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:948",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_canon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590303280,
      "name": "eraser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1191
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
void eraser(unsigned char c, struct tty_struct * tty)
```

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498369904,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:979",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498369904,
      "name": "eraser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1496
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
void eraser(unsigned char c, struct tty_struct * tty)
```

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231060036,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:979",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231060036,
      "name": "eraser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1452
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
void eraser(unsigned char c, struct tty_struct * tty)
```

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291559360,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:979",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291559360,
      "name": "eraser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1912
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
void eraser(unsigned char c, struct tty_struct * tty)
```

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276046166,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:979",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276046166,
      "name": "eraser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1146
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
void eraser(unsigned char c, struct tty_struct * tty)
```

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585454848,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:979",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585454848,
      "name": "eraser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1272
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
void eraser(unsigned char c, struct tty_struct * tty)
```

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585324880,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:979",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585324880,
      "name": "eraser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1272
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
void eraser(unsigned char c, struct tty_struct * tty)
```

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585644224,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:979",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585644224,
      "name": "eraser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1272
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
void eraser(unsigned char c, struct tty_struct * tty)
```

```json
{
  "name": "eraser",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585752352,
      "name": "eraser",
      "external": false,
      "loc": "drivers/tty/n_tty.c:979",
      "file": "drivers/tty/n_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/n_tty.c:n_tty_receive_char_special"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585752352,
      "name": "eraser",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1272
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
void eraser(unsigned char c, struct tty_struct * tty)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned char c</code> ➡️ <code>u8 c</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct tty_struct * tty</code> ➡️ <code>const struct tty_struct * tty</code>
</li>
</ul>
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
