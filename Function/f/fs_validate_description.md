# Function: <code>fs_validate_description</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool fs_validate_description(const struct fs_parameter_description * desc)
```

```json
{
  "name": "fs_validate_description",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582037328,
      "name": "fs_validate_description",
      "external": true,
      "loc": "fs/fs_parser.c:346",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:register_filesystem",
        "security/selinux/hooks.c:selinux_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582037328,
      "name": "fs_validate_description",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
bool fs_validate_description(const struct fs_parameter_description * desc)
```

```json
{
  "name": "fs_validate_description",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582115152,
      "name": "fs_validate_description",
      "external": true,
      "loc": "fs/fs_parser.c:360",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:register_filesystem",
        "security/selinux/hooks.c:selinux_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582115152,
      "name": "fs_validate_description",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool fs_validate_description(const char * name, const struct fs_parameter_spec * desc)
```

```json
{
  "name": "fs_validate_description",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fs_validate_description",
      "external": true,
      "loc": "fs/fs_parser.c:365",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:register_filesystem",
        "security/selinux/hooks.c:selinux_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582352719,
      "name": "fs_validate_description.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582352448,
      "name": "fs_validate_description",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
bool fs_validate_description(const char * name, const struct fs_parameter_spec * desc)
```

```json
{
  "name": "fs_validate_description",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fs_validate_description",
      "external": true,
      "loc": "fs/fs_parser.c:365",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:register_filesystem",
        "security/selinux/hooks.c:selinux_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591340515,
      "name": "fs_validate_description.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582404192,
      "name": "fs_validate_description",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
bool fs_validate_description(const char * name, const struct fs_parameter_spec * desc)
```

```json
{
  "name": "fs_validate_description",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fs_validate_description",
      "external": true,
      "loc": "fs/fs_parser.c:365",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:register_filesystem",
        "security/selinux/hooks.c:selinux_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591283190,
      "name": "fs_validate_description.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582431408,
      "name": "fs_validate_description",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool fs_validate_description(const char * name, const struct fs_parameter_spec * desc)
```

```json
{
  "name": "fs_validate_description",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fs_validate_description",
      "external": true,
      "loc": "fs/fs_parser.c:364",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:register_filesystem",
        "security/selinux/hooks.c:selinux_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592231640,
      "name": "fs_validate_description.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582754176,
      "name": "fs_validate_description",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool fs_validate_description(const char * name, const struct fs_parameter_spec * desc)
```

```json
{
  "name": "fs_validate_description",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fs_validate_description",
      "external": true,
      "loc": "fs/fs_parser.c:379",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:register_filesystem",
        "security/selinux/hooks.c:selinux_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594011614,
      "name": "fs_validate_description.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583302256,
      "name": "fs_validate_description",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
bool fs_validate_description(const char * name, const struct fs_parameter_spec * desc)
```

```json
{
  "name": "fs_validate_description",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583887600,
      "name": "fs_validate_description",
      "external": true,
      "loc": "fs/fs_parser.c:380",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:register_filesystem",
        "security/selinux/hooks.c:selinux_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583887600,
      "name": "fs_validate_description",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
bool fs_validate_description(const char * name, const struct fs_parameter_spec * desc)
```

```json
{
  "name": "fs_validate_description",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584109424,
      "name": "fs_validate_description",
      "external": true,
      "loc": "fs/fs_parser.c:380",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:register_filesystem",
        "security/selinux/hooks.c:selinux_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584109424,
      "name": "fs_validate_description",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
bool fs_validate_description(const char * name, const struct fs_parameter_spec * desc)
```

```json
{
  "name": "fs_validate_description",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584325680,
      "name": "fs_validate_description",
      "external": true,
      "loc": "fs/fs_parser.c:380",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:register_filesystem",
        "security/selinux/hooks.c:selinux_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325680,
      "name": "fs_validate_description",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
bool fs_validate_description(const struct fs_parameter_description * desc)
```

```json
{
  "name": "fs_validate_description",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493656092,
      "name": "fs_validate_description",
      "external": true,
      "loc": "fs/fs_parser.c:360",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:register_filesystem",
        "security/selinux/hooks.c:selinux_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493656092,
      "name": "fs_validate_description",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
bool fs_validate_description(const struct fs_parameter_description * desc)
```

```json
{
  "name": "fs_validate_description",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227190280,
      "name": "fs_validate_description",
      "external": true,
      "loc": "fs/fs_parser.c:360",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:register_filesystem",
        "security/selinux/hooks.c:selinux_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227190280,
      "name": "fs_validate_description",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
bool fs_validate_description(const struct fs_parameter_description * desc)
```

```json
{
  "name": "fs_validate_description",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287253392,
      "name": "fs_validate_description",
      "external": true,
      "loc": "fs/fs_parser.c:360",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:register_filesystem",
        "security/selinux/hooks.c:selinux_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287253392,
      "name": "fs_validate_description",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 712
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
bool fs_validate_description(const struct fs_parameter_description * desc)
```

```json
{
  "name": "fs_validate_description",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273286238,
      "name": "fs_validate_description",
      "external": true,
      "loc": "fs/fs_parser.c:360",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:register_filesystem",
        "security/selinux/hooks.c:selinux_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273286238,
      "name": "fs_validate_description",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
bool fs_validate_description(const struct fs_parameter_description * desc)
```

```json
{
  "name": "fs_validate_description",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582083888,
      "name": "fs_validate_description",
      "external": true,
      "loc": "fs/fs_parser.c:360",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:register_filesystem",
        "security/selinux/hooks.c:selinux_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582083888,
      "name": "fs_validate_description",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
bool fs_validate_description(const struct fs_parameter_description * desc)
```

```json
{
  "name": "fs_validate_description",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582021408,
      "name": "fs_validate_description",
      "external": true,
      "loc": "fs/fs_parser.c:360",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:register_filesystem",
        "security/selinux/hooks.c:selinux_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582021408,
      "name": "fs_validate_description",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fs_validate_description",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fs_validate_description",
      "external": false,
      "loc": "include/linux/fs_parser.h:105",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "fs_validate_description",
      "external": false,
      "loc": "include/linux/fs_parser.h:105",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool fs_validate_description(const struct fs_parameter_description * desc)
```

```json
{
  "name": "fs_validate_description",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582146928,
      "name": "fs_validate_description",
      "external": true,
      "loc": "fs/fs_parser.c:360",
      "file": "fs/fs_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:register_filesystem",
        "security/selinux/hooks.c:selinux_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582146928,
      "name": "fs_validate_description",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
bool fs_validate_description(const struct fs_parameter_description * desc)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char * name</code>
</li>
<li>
<b>Param reordered. </b>
<code>desc</code> ➡️ <code>name, desc</code>
</li>
<li>
<b>Param type changed. </b>
<code>const struct fs_parameter_description * desc</code> ➡️ <code>const struct fs_parameter_spec * desc</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
bool fs_validate_description(const struct fs_parameter_description * desc)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
