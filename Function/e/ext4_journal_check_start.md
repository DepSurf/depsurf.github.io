# Function: <code>ext4_journal_check_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581775504,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:41",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581775504,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581970384,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:41",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581970384,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582060400,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:41",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582060400,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581883984,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:41",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883984,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582034016,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:42",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582034016,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582222352,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:42",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582222352,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582317248,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:42",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582317248,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:42",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582484304,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071582486635,
      "name": "ext4_journal_check_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582583568,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:42",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583568,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582892496,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:64",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582892496,
      "name": "ext4_journal_check_start",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582964832,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:64",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964832,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582990912,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:64",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582990912,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583327104,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:64",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583327104,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583835344,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:64",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583835344,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584458544,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:64",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584458544,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584687440,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:64",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584687440,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584920176,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:64",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584920176,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494232816,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:42",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494232816,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227663264,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:42",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227663264,
      "name": "ext4_journal_check_start",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287932240,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:42",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287932240,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273686184,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:42",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273686184,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582552304,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:42",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582552304,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582489472,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:42",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582489472,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582542416,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:42",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582542416,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int ext4_journal_check_start(struct super_block * sb)
```

```json
{
  "name": "ext4_journal_check_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582623536,
      "name": "ext4_journal_check_start",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.c:42",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582623536,
      "name": "ext4_journal_check_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
