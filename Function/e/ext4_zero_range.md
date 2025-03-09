# Function: <code>ext4_zero_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581771880,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4760",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fallocate"
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
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581966827,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4758",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fallocate"
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
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582056891,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4743",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fallocate"
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
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581919068,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4738",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fallocate"
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
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582069260,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4739",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fallocate"
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
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582257438,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4733",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fallocate"
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
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582353238,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4632",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fallocate"
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
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
```

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582491136,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4642",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582491136,
      "name": "ext4_zero_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1475
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
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
```

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582590672,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4688",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582590672,
      "name": "ext4_zero_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1475
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
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
```

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582903488,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4469",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582903488,
      "name": "ext4_zero_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1341
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
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
```

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582975344,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4466",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582975344,
      "name": "ext4_zero_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1333
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
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
```

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583001120,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4472",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583001120,
      "name": "ext4_zero_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1310
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
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
```

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4511",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583340176,
      "name": "ext4_zero_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1408
    },
    {
      "addr": 18446744071592251340,
      "name": "ext4_zero_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
```

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4507",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583849792,
      "name": "ext4_zero_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1473
    },
    {
      "addr": 18446744071594032367,
      "name": "ext4_zero_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
```

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4511",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584473824,
      "name": "ext4_zero_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1456
    },
    {
      "addr": 18446744071596065648,
      "name": "ext4_zero_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
```

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4503",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584702704,
      "name": "ext4_zero_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1418
    },
    {
      "addr": 18446744071596589545,
      "name": "ext4_zero_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
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
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
```

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4536",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584935328,
      "name": "ext4_zero_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1415
    },
    {
      "addr": 18446744071597495329,
      "name": "ext4_zero_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
```

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494239440,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4688",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494239440,
      "name": "ext4_zero_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1416
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
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
```

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227672908,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4688",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227672908,
      "name": "ext4_zero_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2152
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
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
```

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287944384,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4688",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287944384,
      "name": "ext4_zero_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1972
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
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
```

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273692562,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4688",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273692562,
      "name": "ext4_zero_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1308
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
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
```

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582559408,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4688",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582559408,
      "name": "ext4_zero_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1475
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
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
```

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582496576,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4688",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582496576,
      "name": "ext4_zero_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1475
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
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
```

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582549520,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4688",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582549520,
      "name": "ext4_zero_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1475
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
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
```

```json
{
  "name": "ext4_zero_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582630672,
      "name": "ext4_zero_range",
      "external": false,
      "loc": "fs/ext4/extents.c:4688",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582630672,
      "name": "ext4_zero_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1500
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
long int ext4_zero_range(struct file * file, loff_t offset, loff_t len, int mode)
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
