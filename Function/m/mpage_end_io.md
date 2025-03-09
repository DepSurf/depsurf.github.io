# Function: <code>mpage_end_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581259136,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:45",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581871424,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:101",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581259136,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071581871424,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581424880,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:46",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582067792,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:70",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581424880,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071582067792,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581505968,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:46",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582157824,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:70",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505968,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071582157824,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581558448,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:46",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582115520,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:70",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558448,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071582115520,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581702224,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:47",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582264576,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:71",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581702224,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071582264576,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581868992,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:47",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582452608,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:71",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868992,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071582452608,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581954048,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:47",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582552080,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:71",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954048,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071582552080,
      "name": "mpage_end_io",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582086624,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:47",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582724448,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:71",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582086624,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071582724448,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582164064,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:47",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582827440,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:174",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582164064,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071582827440,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582401008,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:47",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583138912,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:174",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582401008,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071583138912,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582454000,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:47",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583219648,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:174",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582454000,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071583219648,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582481056,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:47",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583247488,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:174",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582481056,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071583247488,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582794016,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:47",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583589456,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:174",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582794016,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071583589456,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583346304,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:46",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584128496,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:173",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583346304,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071584128496,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583929776,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:46",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584762336,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:171",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583929776,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071584762336,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584986032,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:169",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584986032,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585217664,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:162",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585217664,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493718456,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:47",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494499944,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:174",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493718456,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446603336494499944,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227244512,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:47",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227935752,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:174",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227244512,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 3227935752,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287324000,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:47",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055288264896,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:174",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287324000,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    },
    {
      "addr": 13835058055288264896,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273330504,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:47",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273897994,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:174",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273897994,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446743936273330504,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582132800,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:47",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582796176,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:174",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582132800,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071582796176,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582070240,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:47",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582733328,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:174",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582070240,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071582733328,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582123280,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:47",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582785056,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:174",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123280,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071582785056,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
void mpage_end_io(struct bio * bio)
```

```json
{
  "name": "mpage_end_io",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582196272,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/mpage.c:47",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582871456,
      "name": "mpage_end_io",
      "external": false,
      "loc": "fs/ext4/readpage.c:174",
      "file": "fs/ext4/readpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582196272,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071582871456,
      "name": "mpage_end_io",
      "section": ".text",
      "bind": "STB_LOCAL",
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
