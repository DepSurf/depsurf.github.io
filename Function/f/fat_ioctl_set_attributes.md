# Function: <code>fat_ioctl_set_attributes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581970215,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:30",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582182423,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:34",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582271847,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:34",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582356377,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:34",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582507173,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:34",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582698404,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:34",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582801622,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:34",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
```

```json
{
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582976288,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:35",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582976288,
      "name": "fat_ioctl_set_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
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
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
```

```json
{
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583082496,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:35",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583082496,
      "name": "fat_ioctl_set_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
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
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
```

```json
{
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583401168,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:35",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583401168,
      "name": "fat_ioctl_set_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 995
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
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
```

```json
{
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583516688,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:35",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583516688,
      "name": "fat_ioctl_set_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1062
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
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
```

```json
{
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583539648,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:35",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583539648,
      "name": "fat_ioctl_set_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1090
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
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
```

```json
{
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583897632,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:35",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583897632,
      "name": "fat_ioctl_set_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1106
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
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
```

```json
{
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584474368,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:35",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584474368,
      "name": "fat_ioctl_set_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1174
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
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
```

```json
{
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585138400,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:35",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585138400,
      "name": "fat_ioctl_set_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1196
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
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
```

```json
{
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585367504,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:35",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585367504,
      "name": "fat_ioctl_set_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1199
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
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
```

```json
{
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585602240,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:35",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585602240,
      "name": "fat_ioctl_set_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1199
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
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
```

```json
{
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494787672,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:35",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494787672,
      "name": "fat_ioctl_set_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1300
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
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
```

```json
{
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228208156,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:35",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228208156,
      "name": "fat_ioctl_set_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1004
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
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
```

```json
{
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288622944,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:35",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288622944,
      "name": "fat_ioctl_set_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1400
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
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274119532,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:35",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
```

```json
{
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583051232,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:35",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583051232,
      "name": "fat_ioctl_set_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
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
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
```

```json
{
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582988384,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:35",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582988384,
      "name": "fat_ioctl_set_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
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
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
```

```json
{
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583039840,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:35",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583039840,
      "name": "fat_ioctl_set_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
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
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
```

```json
{
  "name": "fat_ioctl_set_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583128976,
      "name": "fat_ioctl_set_attributes",
      "external": false,
      "loc": "fs/fat/file.c:35",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583128976,
      "name": "fat_ioctl_set_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
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
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int fat_ioctl_set_attributes(struct file * file, u32 * user_attr)
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
