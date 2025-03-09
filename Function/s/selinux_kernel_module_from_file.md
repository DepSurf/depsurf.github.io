# Function: <code>selinux_kernel_module_from_file</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582489048,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:3764",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_kernel_read_file"
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
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582581830,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:3836",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_kernel_read_file"
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
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582672998,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:3794",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_kernel_read_file"
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
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582827190,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:3809",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_kernel_read_file"
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
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583038999,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:4027",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_kernel_read_file"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583153520,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:3733",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583153520,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583340304,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:3921",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583340304,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583445664,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:3979",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583445664,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583775181,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:3972",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583788528,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583893613,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:3986",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583910592,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583919677,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:4145",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583938720,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584283261,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:4130",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584304416,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584901839,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:4026",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584919424,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585609759,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:4044",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585628256,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585840204,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:4020",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585858320,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586089148,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:4107",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586108048,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
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
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495206688,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:3979",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495206688,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228581044,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:3979",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228581044,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289143008,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:3979",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289143008,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274441492,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:3979",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274441492,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583414400,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:3979",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583414400,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583351472,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:3979",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583351472,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583398176,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:3979",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583398176,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int selinux_kernel_module_from_file(struct file * file)
```

```json
{
  "name": "selinux_kernel_module_from_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583484032,
      "name": "selinux_kernel_module_from_file",
      "external": false,
      "loc": "security/selinux/hooks.c:3979",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583484032,
      "name": "selinux_kernel_module_from_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int selinux_kernel_module_from_file(struct file * file)
```
</details>
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
