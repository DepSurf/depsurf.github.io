# Function: <code>find_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594952053,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:70",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595115823,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:70",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595358897,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:70",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596275696,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:71",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602591728,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:72",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602760725,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:72",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
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
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604554842,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:62",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
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
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604649116,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:62",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
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
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604661377,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:62",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
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
char * find_link(int major, int minor, int ino, umode_t mode, char * name)
```

```json
{
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609011201,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:63",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609011201,
      "name": "find_link",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 235
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
char * find_link(int major, int minor, int ino, umode_t mode, char * name)
```

```json
{
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612073304,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:66",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612073304,
      "name": "find_link",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 235
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
char * find_link(int major, int minor, int ino, umode_t mode, char * name)
```

```json
{
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614211529,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:78",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614211529,
      "name": "find_link",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 235
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
char * find_link(int major, int minor, int ino, umode_t mode, char * name)
```

```json
{
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615130273,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:79",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615130273,
      "name": "find_link",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 235
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
char * find_link(int major, int minor, int ino, umode_t mode, char * name)
```

```json
{
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616893469,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:90",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616893469,
      "name": "find_link",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 293
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
char * find_link(int major, int minor, int ino, umode_t mode, char * name)
```

```json
{
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627484192,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:90",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627484192,
      "name": "find_link",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 316
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
char * find_link(int major, int minor, int ino, umode_t mode, char * name)
```

```json
{
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619228208,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:84",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619228208,
      "name": "find_link",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 330
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
char * find_link(int major, int minor, int ino, umode_t mode, char * name)
```

```json
{
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621517840,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:84",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621517840,
      "name": "find_link",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 377
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
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510811956,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:62",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
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
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243257912,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:62",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
char * find_link(int major, int minor, int ino, umode_t mode, char * name)
```

```json
{
  "name": "find_link",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302376080,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:62",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283106672,
      "name": "find_link",
      "external": false,
      "loc": "arch/powerpc/platforms/powernv/ocxl.c:138",
      "file": "arch/powerpc/platforms/powernv/ocxl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_get_pasid_count",
        "arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_fixup_actag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283106672,
      "name": "find_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270608792,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:62",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
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
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604587649,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:62",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
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
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604579326,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:62",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
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
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604665473,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:62",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
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
  "name": "find_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604665478,
      "name": "find_link",
      "external": false,
      "loc": "init/initramfs.c:62",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
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
char * find_link(int major, int minor, int ino, umode_t mode, char * name)
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
char * find_link(int major, int minor, int ino, umode_t mode, char * name)
```
</details>
</li>
</ul>
