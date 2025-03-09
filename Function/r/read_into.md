# Function: <code>read_into</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594951150,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:215",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
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
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595114895,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:215",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
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
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595357969,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:215",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
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
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596277291,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:216",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:do_start"
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
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602593323,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:217",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:do_start"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void read_into(char * buf, unsigned int size, enum state next)
```

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602758550,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:217",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602758550,
      "name": "read_into",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 91
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
void read_into(char * buf, unsigned int size, enum state next)
```

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604552665,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:207",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604552665,
      "name": "read_into",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 91
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
void read_into(char * buf, unsigned int size, enum state next)
```

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604646954,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:207",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604646954,
      "name": "read_into",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 96
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
void read_into(char * buf, unsigned int size, enum state next)
```

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604659215,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:207",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604659215,
      "name": "read_into",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 96
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
void read_into(char * buf, unsigned int size, enum state next)
```

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609010464,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:208",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609010464,
      "name": "read_into",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 96
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
void read_into(char * buf, unsigned int size, enum state next)
```

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612072533,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:209",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612072533,
      "name": "read_into",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 96
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
void read_into(char * buf, unsigned int size, enum state next)
```

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614210744,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:221",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614210744,
      "name": "read_into",
      "section": ".init.text",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void read_into(char * buf, unsigned int size, enum state next)
```

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615129462,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:222",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615129462,
      "name": "read_into",
      "section": ".init.text",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void read_into(char * buf, unsigned int size, enum state next)
```

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616891653,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:245",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616891653,
      "name": "read_into",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627486031,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:245",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619230063,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:239",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621519999,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:239",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void read_into(char * buf, unsigned int size, enum state next)
```

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510809540,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:207",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510809540,
      "name": "read_into",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 120
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
void read_into(char * buf, unsigned int size, enum state next)
```

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243255368,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:207",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243255368,
      "name": "read_into",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 92
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
void read_into(char * buf, unsigned int size, enum state next)
```

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302372872,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:207",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302372872,
      "name": "read_into",
      "section": ".init.text",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void read_into(char * buf, unsigned int size, enum state next)
```

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270606790,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:207",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270606790,
      "name": "read_into",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 106
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
void read_into(char * buf, unsigned int size, enum state next)
```

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604585487,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:207",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604585487,
      "name": "read_into",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 96
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
void read_into(char * buf, unsigned int size, enum state next)
```

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604577164,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:207",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604577164,
      "name": "read_into",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 96
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
void read_into(char * buf, unsigned int size, enum state next)
```

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604663311,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:207",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604663311,
      "name": "read_into",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 96
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
void read_into(char * buf, unsigned int size, enum state next)
```

```json
{
  "name": "read_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604663316,
      "name": "read_into",
      "external": false,
      "loc": "init/initramfs.c:207",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604663316,
      "name": "read_into",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 96
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void read_into(char * buf, unsigned int size, enum state next)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void read_into(char * buf, unsigned int size, enum state next)
```
</details>
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
