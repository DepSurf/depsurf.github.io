# Function: <code>reconfigure_single</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reconfigure_single",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581793751,
      "name": "reconfigure_single",
      "external": false,
      "loc": "fs/super.c:1367",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_single"
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
  "name": "reconfigure_single",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581866471,
      "name": "reconfigure_single",
      "external": false,
      "loc": "fs/super.c:1473",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_single"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reconfigure_single",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582092535,
      "name": "reconfigure_single",
      "external": false,
      "loc": "fs/super.c:1473",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_single"
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
  "name": "reconfigure_single",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582138935,
      "name": "reconfigure_single",
      "external": false,
      "loc": "fs/super.c:1422",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_single"
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
  "name": "reconfigure_single",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582163719,
      "name": "reconfigure_single",
      "external": false,
      "loc": "fs/super.c:1424",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_single"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int reconfigure_single(struct super_block * s, int flags, void * data)
```

```json
{
  "name": "reconfigure_single",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582480695,
      "name": "reconfigure_single",
      "external": true,
      "loc": "fs/super.c:1424",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_single"
      ],
      "caller_func": [
        "drivers/base/devtmpfs.c:public_dev_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582481056,
      "name": "reconfigure_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int reconfigure_single(struct super_block * s, int flags, void * data)
```

```json
{
  "name": "reconfigure_single",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583001557,
      "name": "reconfigure_single",
      "external": true,
      "loc": "fs/super.c:1423",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_single"
      ],
      "caller_func": [
        "drivers/base/devtmpfs.c:public_dev_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583001968,
      "name": "reconfigure_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int reconfigure_single(struct super_block * s, int flags, void * data)
```

```json
{
  "name": "reconfigure_single",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583563253,
      "name": "reconfigure_single",
      "external": true,
      "loc": "fs/super.c:1428",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_single"
      ],
      "caller_func": [
        "drivers/base/devtmpfs.c:public_dev_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583563712,
      "name": "reconfigure_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int reconfigure_single(struct super_block * s, int flags, void * data)
```

```json
{
  "name": "reconfigure_single",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583779557,
      "name": "reconfigure_single",
      "external": true,
      "loc": "fs/super.c:1445",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_single"
      ],
      "caller_func": [
        "drivers/base/devtmpfs.c:public_dev_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583780016,
      "name": "reconfigure_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int reconfigure_single(struct super_block * s, int flags, void * data)
```

```json
{
  "name": "reconfigure_single",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583985077,
      "name": "reconfigure_single",
      "external": true,
      "loc": "fs/super.c:1705",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_single"
      ],
      "caller_func": [
        "drivers/base/devtmpfs.c:public_dev_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583985632,
      "name": "reconfigure_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
  "name": "reconfigure_single",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493338164,
      "name": "reconfigure_single",
      "external": false,
      "loc": "fs/super.c:1473",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_single"
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
  "name": "reconfigure_single",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226932236,
      "name": "reconfigure_single",
      "external": false,
      "loc": "fs/super.c:1473",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_single"
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
  "name": "reconfigure_single",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286881656,
      "name": "reconfigure_single",
      "external": false,
      "loc": "fs/super.c:1473",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_single"
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
  "name": "reconfigure_single",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273068870,
      "name": "reconfigure_single",
      "external": false,
      "loc": "fs/super.c:1473",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_single"
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
  "name": "reconfigure_single",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581835207,
      "name": "reconfigure_single",
      "external": false,
      "loc": "fs/super.c:1473",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_single"
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
  "name": "reconfigure_single",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581772871,
      "name": "reconfigure_single",
      "external": false,
      "loc": "fs/super.c:1473",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_single"
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
  "name": "reconfigure_single",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581826519,
      "name": "reconfigure_single",
      "external": false,
      "loc": "fs/super.c:1473",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_single"
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
  "name": "reconfigure_single",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581895703,
      "name": "reconfigure_single",
      "external": false,
      "loc": "fs/super.c:1473",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_single"
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int reconfigure_single(struct super_block * s, int flags, void * data)
```
</details>
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
