# Function: <code>verify_group_input</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581732999,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:85",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_group_add"
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
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581928076,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:85",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_group_add"
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
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582018140,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:85",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_group_add"
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
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582127441,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:86",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_group_add"
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
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582276753,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:87",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_group_add"
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
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582464753,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:88",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_group_add"
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
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582564145,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:88",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_group_add"
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
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
```

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582727280,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:88",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582727280,
      "name": "verify_group_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1103
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
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
```

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582830512,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:115",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582830512,
      "name": "verify_group_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1103
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
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
```

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583148832,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:115",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583148832,
      "name": "verify_group_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1170
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
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
```

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583230016,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:115",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583230016,
      "name": "verify_group_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1184
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
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
```

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583258432,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:115",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583258432,
      "name": "verify_group_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1182
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
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
```

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583601152,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:120",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583601152,
      "name": "verify_group_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1182
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
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
```

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584137584,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:131",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584137584,
      "name": "verify_group_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1194
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
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
```

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584771696,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:134",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584771696,
      "name": "verify_group_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1183
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
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
```

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584995088,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:134",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584995088,
      "name": "verify_group_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
```

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:120",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585227088,
      "name": "verify_group_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1207
    },
    {
      "addr": 18446744071597511646,
      "name": "verify_group_input.cold",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
```

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494502784,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:115",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494502784,
      "name": "verify_group_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1140
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
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
```

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227938844,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:115",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227938844,
      "name": "verify_group_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1576
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
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
```

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288268096,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:115",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288268096,
      "name": "verify_group_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1340
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
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
```

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273900200,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:115",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273900200,
      "name": "verify_group_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 944
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
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
```

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582799248,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:115",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582799248,
      "name": "verify_group_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1103
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
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
```

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582736400,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:115",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582736400,
      "name": "verify_group_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1103
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
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
```

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582788128,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:115",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582788128,
      "name": "verify_group_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1103
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
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
```

```json
{
  "name": "verify_group_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582874576,
      "name": "verify_group_input",
      "external": false,
      "loc": "fs/ext4/resize.c:115",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582874576,
      "name": "verify_group_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1103
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
int verify_group_input(struct super_block * sb, struct ext4_new_group_data * input)
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
