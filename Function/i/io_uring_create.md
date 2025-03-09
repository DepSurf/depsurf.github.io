# Function: <code>io_uring_create</code>

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
int io_uring_create(unsigned int entries, struct io_uring_params * p)
```

```json
{
  "name": "io_uring_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582191152,
      "name": "io_uring_create",
      "external": false,
      "loc": "fs/io_uring.c:3324",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191152,
      "name": "io_uring_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1897
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
int io_uring_create(unsigned int entries, struct io_uring_params * p)
```

```json
{
  "name": "io_uring_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582272032,
      "name": "io_uring_create",
      "external": false,
      "loc": "fs/io_uring.c:3882",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582272032,
      "name": "io_uring_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1969
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
int io_uring_create(unsigned int entries, struct io_uring_params * p, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582537456,
      "name": "io_uring_create",
      "external": false,
      "loc": "fs/io_uring.c:8154",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582537456,
      "name": "io_uring_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1128
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
int io_uring_create(unsigned int entries, struct io_uring_params * p, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582607136,
      "name": "io_uring_create",
      "external": false,
      "loc": "fs/io_uring.c:9650",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582607136,
      "name": "io_uring_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1803
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
int io_uring_create(unsigned int entries, struct io_uring_params * p, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582620592,
      "name": "io_uring_create",
      "external": false,
      "loc": "fs/io_uring.c:9624",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582620592,
      "name": "io_uring_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1261
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
int io_uring_create(unsigned int entries, struct io_uring_params * p, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_uring_create",
      "external": false,
      "loc": "fs/io_uring.c:10297",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582944368,
      "name": "io_uring_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1329
    },
    {
      "addr": 18446744071592238054,
      "name": "io_uring_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
int io_uring_create(unsigned int entries, struct io_uring_params * p, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594124532,
      "name": "io_uring_create",
      "external": false,
      "loc": "io_uring/io_uring.c:11955",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594124532,
      "name": "io_uring_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 951
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
int io_uring_create(unsigned int entries, struct io_uring_params * p, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_uring_create",
      "external": false,
      "loc": "io_uring/io_uring.c:3529",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586761344,
      "name": "io_uring_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1308
    },
    {
      "addr": 18446744071596111219,
      "name": "io_uring_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int io_uring_create(unsigned int entries, struct io_uring_params * p, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_uring_create",
      "external": false,
      "loc": "io_uring/io_uring.c:3817",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587027856,
      "name": "io_uring_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1349
    },
    {
      "addr": 18446744071596635570,
      "name": "io_uring_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int io_uring_create(unsigned int entries, struct io_uring_params * p, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_uring_create",
      "external": false,
      "loc": "io_uring/io_uring.c:3822",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587325792,
      "name": "io_uring_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1274
    },
    {
      "addr": 18446744071597543656,
      "name": "io_uring_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int io_uring_create(unsigned int entries, struct io_uring_params * p)
```

```json
{
  "name": "io_uring_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493837912,
      "name": "io_uring_create",
      "external": false,
      "loc": "fs/io_uring.c:3882",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493837912,
      "name": "io_uring_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1692
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
int io_uring_create(unsigned int entries, struct io_uring_params * p)
```

```json
{
  "name": "io_uring_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227345644,
      "name": "io_uring_create",
      "external": false,
      "loc": "fs/io_uring.c:3882",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227345644,
      "name": "io_uring_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1952
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
int io_uring_create(unsigned int entries, struct io_uring_params * p)
```

```json
{
  "name": "io_uring_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287469952,
      "name": "io_uring_create",
      "external": false,
      "loc": "fs/io_uring.c:3882",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287469952,
      "name": "io_uring_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2036
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
int io_uring_create(unsigned int entries, struct io_uring_params * p)
```

```json
{
  "name": "io_uring_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273417736,
      "name": "io_uring_create",
      "external": false,
      "loc": "fs/io_uring.c:3882",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273417736,
      "name": "io_uring_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1602
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
int io_uring_create(unsigned int entries, struct io_uring_params * p)
```

```json
{
  "name": "io_uring_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582240768,
      "name": "io_uring_create",
      "external": false,
      "loc": "fs/io_uring.c:3882",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582240768,
      "name": "io_uring_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1969
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
int io_uring_create(unsigned int entries, struct io_uring_params * p)
```

```json
{
  "name": "io_uring_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582178496,
      "name": "io_uring_create",
      "external": false,
      "loc": "fs/io_uring.c:3882",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582178496,
      "name": "io_uring_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1969
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
int io_uring_create(unsigned int entries, struct io_uring_params * p)
```

```json
{
  "name": "io_uring_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582231248,
      "name": "io_uring_create",
      "external": false,
      "loc": "fs/io_uring.c:3882",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582231248,
      "name": "io_uring_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1969
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
int io_uring_create(unsigned int entries, struct io_uring_params * p)
```

```json
{
  "name": "io_uring_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582309504,
      "name": "io_uring_create",
      "external": false,
      "loc": "fs/io_uring.c:3882",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582309504,
      "name": "io_uring_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1969
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
int io_uring_create(unsigned int entries, struct io_uring_params * p)
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
<code>struct io_uring_params * params</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
