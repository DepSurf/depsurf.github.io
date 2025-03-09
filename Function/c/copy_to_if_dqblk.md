# Function: <code>copy_to_if_dqblk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581423149,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:189",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quota_getquota"
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
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581606027,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:189",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
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
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581694555,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:185",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581744544,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:185",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581744544,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581891600,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:186",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581891600,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582074864,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:187",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582074864,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582169232,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:185",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582169232,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582332112,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:185",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582332112,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582431296,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:185",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582431296,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582726336,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:183",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582726336,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582798304,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:185",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582798304,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582825904,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:186",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582825904,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583157968,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:186",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583157968,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583652253,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:187",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584258253,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:187",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584484384,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:187",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584484384,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584707344,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:187",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584707344,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494043856,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:185",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494043856,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227504416,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:185",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227504416,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287698736,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:185",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287698736,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273550496,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:185",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
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
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582400032,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:185",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582400032,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582337728,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:185",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582337728,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582390512,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:185",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582390512,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```

```json
{
  "name": "copy_to_if_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582470048,
      "name": "copy_to_if_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:185",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470048,
      "name": "copy_to_if_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```
</details>
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
```
</details>
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
void copy_to_if_dqblk(struct if_dqblk * dst, struct qc_dqblk * src)
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
