# Function: <code>fscrypt_file_open</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581796992,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:30",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796992,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:30",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581972264,
      "name": "fscrypt_file_open.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071581972112,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:30",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059316,
      "name": "fscrypt_file_open.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071582059168,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:30",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582220416,
      "name": "fscrypt_file_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071582220240,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:30",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582302439,
      "name": "fscrypt_file_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071582302288,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582586816,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:32",
      "file": "fs/crypto/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582587662,
      "name": "fscrypt_file_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071582586784,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582657904,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:32",
      "file": "fs/crypto/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591341586,
      "name": "fscrypt_file_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071582657872,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582687152,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:32",
      "file": "fs/crypto/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591284319,
      "name": "fscrypt_file_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071582687120,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583012864,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:32",
      "file": "fs/crypto/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592240174,
      "name": "fscrypt_file_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071583012832,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583483583,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:32",
      "file": "fs/crypto/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594018972,
      "name": "fscrypt_file_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583483552,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584078448,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:30",
      "file": "fs/crypto/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584078448,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584305232,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:30",
      "file": "fs/crypto/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584305232,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584522256,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:30",
      "file": "fs/crypto/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584522256,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493877816,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:30",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493877816,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227360188,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:30",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227360188,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287512704,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:30",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287512704,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273441580,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:30",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273441580,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:30",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271175,
      "name": "fscrypt_file_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071582271024,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:30",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208935,
      "name": "fscrypt_file_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071582208784,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:30",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582261655,
      "name": "fscrypt_file_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071582261504,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_file_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "fscrypt_file_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_file_open",
      "external": true,
      "loc": "fs/crypto/hooks.c:30",
      "file": "fs/crypto/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340247,
      "name": "fscrypt_file_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071582340096,
      "name": "fscrypt_file_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int fscrypt_file_open(struct inode * inode, struct file * filp)
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
