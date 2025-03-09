# Function: <code>lzo_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int lzo_init(struct crypto_tfm * tfm)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582693712,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:30",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582693712,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582147440,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:41",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582953904,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:30",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582147440,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071582953904,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582236960,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:41",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583058432,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:44",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582236960,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071583058432,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582321696,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:41",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583113520,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:42",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582321696,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071583113520,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582471136,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:41",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583287456,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:42",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471136,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071583287456,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:41",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583495904,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:42",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582662096,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071582662228,
      "name": "lzo_init.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583495904,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:41",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583617168,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:42",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582763984,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071582764116,
      "name": "lzo_init.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583617168,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:28",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583803264,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:29",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582938240,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071582938376,
      "name": "lzo_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583803264,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:28",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583905104,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:29",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583044864,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071583045000,
      "name": "lzo_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583905104,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:28",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584294928,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:29",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583363216,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071583363352,
      "name": "lzo_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584294928,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:28",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584413536,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:29",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583479376,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071591351889,
      "name": "lzo_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584413536,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:28",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584448464,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:29",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583501584,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    },
    {
      "addr": 18446744071591294804,
      "name": "lzo_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584448464,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:28",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584846464,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:29",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583856512,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    },
    {
      "addr": 18446744071592276611,
      "name": "lzo_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584846464,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:28",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585539968,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:29",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584426880,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071594058544,
      "name": "lzo_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071585539968,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585087840,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:28",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586302096,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:29",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585087840,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071586302096,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585317456,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:28",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586545712,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:29",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585317456,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071586545712,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585551952,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:28",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586815792,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:29",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585551952,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071586815792,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494740576,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:28",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495726024,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:29",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494740576,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336495726024,
      "name": "lzo_init",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228176424,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:28",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229079864,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:29",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228176424,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 3229079864,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288568240,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:28",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289880176,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:29",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288568240,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 13835058055289880176,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274086948,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:28",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274877406,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:29",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274877406,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446743936274086948,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Transformation ❓</summary>

```c
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:28",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583873840,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:29",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583013600,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071583013736,
      "name": "lzo_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583873840,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Transformation ❓</summary>

```c
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:28",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583810896,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:29",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582950752,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071582950888,
      "name": "lzo_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583810896,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Transformation ❓</summary>

```c
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:28",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583857600,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:29",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002208,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071583002344,
      "name": "lzo_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583857600,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Transformation ❓</summary>

```c
void * lzo_init(struct squashfs_sb_info * msblk, void * buff)
```

```json
{
  "name": "lzo_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lzo_init",
      "external": false,
      "loc": "fs/squashfs/lzo_wrapper.c:28",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583958672,
      "name": "lzo_init",
      "external": false,
      "loc": "crypto/lzo.c:29",
      "file": "crypto/lzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583091440,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071583091576,
      "name": "lzo_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583958672,
      "name": "lzo_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
<b>Param added. </b>
<code>struct squashfs_sb_info * msblk</code>
</li>
<li>
<b>Param added. </b>
<code>void * buff</code>
</li>
<li>
<b>Param removed. </b>
<code>struct crypto_tfm * tfm</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void *</code>
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
