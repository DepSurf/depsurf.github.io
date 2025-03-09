# Function: <code>shmem_get_unmapped_area</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580672592,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:1937",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580672592,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580739616,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:1974",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580739616,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 605
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580770800,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2011",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580770800,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580858128,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2022",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580858128,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580995072,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2041",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995072,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 601
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581072496,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2003",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581072496,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 601
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136048,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2065",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136048,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 601
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581193792,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2081",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581193792,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581383632,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2059",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581383632,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 722
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581427232,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2121",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581427232,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 722
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581448688,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2123",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448688,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 631
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581703008,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2125",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581703008,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 631
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582074544,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2124",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582074544,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 669
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582562352,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2144",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582562352,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 655
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582768224,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2174",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582768224,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582943280,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2239",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943280,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492576848,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2081",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492576848,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226444092,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2081",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226444092,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285885184,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2081",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285885184,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 760
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272619370,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2081",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272619370,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581162640,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2081",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581162640,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581109488,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2081",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581109488,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581153840,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2081",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581153840,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "shmem_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581216768,
      "name": "shmem_get_unmapped_area",
      "external": true,
      "loc": "mm/shmem.c:2081",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216768,
      "name": "shmem_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
long unsigned int shmem_get_unmapped_area(struct file * file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
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
