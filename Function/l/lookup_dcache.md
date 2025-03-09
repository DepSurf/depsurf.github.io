# Function: <code>lookup_dcache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * lookup_dcache(struct qstr * name, struct dentry * dir, unsigned int flags, bool * need_lookup)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581039728,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1451",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__lookup_hash",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581039728,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194240,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1472",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194240,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581271456,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1468",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271456,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581326208,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1480",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326208,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581466320,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1478",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581466320,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581623408,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1463",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:__lookup_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581623408,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581709632,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1504",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:__lookup_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581709632,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581827392,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1502",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:__lookup_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827392,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581899952,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1497",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:__lookup_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899952,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582129312,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1403",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:__lookup_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582129312,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582175840,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1403",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:__lookup_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582175840,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582199120,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1488",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:__lookup_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582199120,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582516448,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1516",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:__lookup_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582516448,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583040880,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1562",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:__lookup_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583040880,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583606240,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1559",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:__lookup_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583606240,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583825440,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1562",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:lookup_one_qstr_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583825440,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584031552,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1565",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:lookup_one_qstr_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584031552,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493380032,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1497",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:__lookup_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493380032,
      "name": "lookup_dcache",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226968736,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1497",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:__lookup_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226968736,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286933728,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1497",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:__lookup_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286933728,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273097298,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1497",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:__lookup_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273097298,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581868688,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1497",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:__lookup_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868688,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581806288,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1497",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:__lookup_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581806288,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581860000,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1497",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:__lookup_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581860000,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
struct dentry * lookup_dcache(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_dcache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581931776,
      "name": "lookup_dcache",
      "external": false,
      "loc": "fs/namei.c:1497",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len",
        "fs/namei.c:__lookup_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581931776,
      "name": "lookup_dcache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool * need_lookup</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct qstr * name</code> ➡️ <code>const struct qstr * name</code>
</li>
</ul>
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
