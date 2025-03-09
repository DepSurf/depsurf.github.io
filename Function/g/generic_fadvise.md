# Function: <code>generic_fadvise</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "generic_fadvise",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580966944,
      "name": "generic_fadvise",
      "external": false,
      "loc": "mm/fadvise.c:30",
      "file": "mm/fadvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:vfs_fadvise"
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
  "name": "generic_fadvise",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581062048,
      "name": "generic_fadvise",
      "external": false,
      "loc": "mm/fadvise.c:30",
      "file": "mm/fadvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:vfs_fadvise"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int generic_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "generic_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581117744,
      "name": "generic_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:30",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:vfs_fadvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581117744,
      "name": "generic_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
int generic_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "generic_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581301488,
      "name": "generic_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:32",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581301488,
      "name": "generic_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
int generic_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "generic_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581344640,
      "name": "generic_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:32",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581344640,
      "name": "generic_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 673
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
int generic_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "generic_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581363728,
      "name": "generic_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:32",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581363728,
      "name": "generic_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 677
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
int generic_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "generic_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581612112,
      "name": "generic_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:32",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612112,
      "name": "generic_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
int generic_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "generic_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581972384,
      "name": "generic_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:32",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581972384,
      "name": "generic_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
int generic_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "generic_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582406848,
      "name": "generic_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:32",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582406848,
      "name": "generic_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 681
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
int generic_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "generic_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582612832,
      "name": "generic_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:31",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582612832,
      "name": "generic_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 735
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
int generic_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "generic_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582784400,
      "name": "generic_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:31",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582784400,
      "name": "generic_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 735
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
int generic_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "generic_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492486536,
      "name": "generic_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:30",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:vfs_fadvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492486536,
      "name": "generic_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
int generic_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "generic_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226359680,
      "name": "generic_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:30",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:vfs_fadvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226359680,
      "name": "generic_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
int generic_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "generic_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285772656,
      "name": "generic_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:30",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:vfs_fadvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285772656,
      "name": "generic_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1072
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
int generic_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "generic_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272550850,
      "name": "generic_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:30",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:vfs_fadvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272550850,
      "name": "generic_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
int generic_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "generic_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581086592,
      "name": "generic_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:30",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:vfs_fadvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581086592,
      "name": "generic_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
int generic_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "generic_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581033776,
      "name": "generic_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:30",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:vfs_fadvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581033776,
      "name": "generic_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
int generic_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "generic_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581077792,
      "name": "generic_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:30",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:vfs_fadvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077792,
      "name": "generic_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
int generic_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "generic_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139680,
      "name": "generic_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:30",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:vfs_fadvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139680,
      "name": "generic_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int generic_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```
</details>
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
