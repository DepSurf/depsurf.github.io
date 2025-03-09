# Function: <code>ima_read_file</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int ima_read_file(struct file * file, enum kernel_read_file_id read_id)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582857968,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:358",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582857968,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582954800,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:360",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582954800,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583004768,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:360",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583004768,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583168880,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:363",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583168880,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:430",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583375408,
      "name": "ima_read_file.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583375056,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583493776,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:432",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583493776,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583680720,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:492",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583680720,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583787600,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:512",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583787600,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584178752,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:611",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584178752,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id, bool contents)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584297760,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:658",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584297760,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id, bool contents)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584331824,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:671",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584331824,
      "name": "ima_read_file",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int ima_read_file(struct file * file, enum kernel_read_file_id read_id, bool contents)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584719536,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:688",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584719536,
      "name": "ima_read_file",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int ima_read_file(struct file * file, enum kernel_read_file_id read_id, bool contents)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585394592,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:711",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585394592,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id, bool contents)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586147472,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:721",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586147472,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id, bool contents)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586385680,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:740",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586385680,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id, bool contents)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586650512,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:754",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586650512,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495590672,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:512",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495590672,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228951540,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:512",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228951540,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289691680,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:512",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289691680,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274754836,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:512",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274754836,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583756336,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:512",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583756336,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583693392,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:512",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583693392,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583740112,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:512",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583740112,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int ima_read_file(struct file * file, enum kernel_read_file_id read_id)
```

```json
{
  "name": "ima_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583841040,
      "name": "ima_read_file",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:512",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583841040,
      "name": "ima_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int ima_read_file(struct file * file, enum kernel_read_file_id read_id)
```
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool contents</code>
</li>
</ul>
</details>
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
