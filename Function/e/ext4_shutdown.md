# Function: <code>ext4_shutdown</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582026639,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:458",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582177286,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:467",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582369196,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:464",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582467540,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:523",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582637104,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:572",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582740502,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:570",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ext4_shutdown(struct super_block * sb, long unsigned int arg)
```

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583044448,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:601",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583044448,
      "name": "ext4_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int ext4_shutdown(struct super_block * sb, long unsigned int arg)
```

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583120416,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:603",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583120416,
      "name": "ext4_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
int ext4_shutdown(struct super_block * sb, long unsigned int arg)
```

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583145616,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:557",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583145616,
      "name": "ext4_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
int ext4_shutdown(struct super_block * sb, long unsigned int arg)
```

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583486080,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:556",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583486080,
      "name": "ext4_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
int ext4_shutdown(struct super_block * sb, long unsigned int arg)
```

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584009008,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:785",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584009008,
      "name": "ext4_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
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
int ext4_shutdown(struct super_block * sb, long unsigned int arg)
```

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584639200,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:798",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584639200,
      "name": "ext4_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
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
void ext4_shutdown(struct super_block * sb)
```

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585093248,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/super.c:1457",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585093248,
      "name": "ext4_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void ext4_shutdown(struct super_block * sb)
```

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585325008,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/super.c:1483",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585325008,
      "name": "ext4_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494401380,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:570",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227836556,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:570",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288136620,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:570",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273819980,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:570",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582709238,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:570",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582646406,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:570",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582699094,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:570",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582783478,
      "name": "ext4_shutdown",
      "external": false,
      "loc": "fs/ext4/ioctl.c:570",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ext4_shutdown(struct super_block * sb, long unsigned int arg)
```
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int arg</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
