# Function: <code>do_brk_flags</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int do_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580933632,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:2864",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:SyS_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933632,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 807
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
int do_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581033392,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:2890",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:SyS_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581033392,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 807
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581168000,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:2945",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581168000,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 751
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248048,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:2997",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248048,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322672,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:3003",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322672,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 833
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581382016,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:3009",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581382016,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 833
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581578144,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:3019",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581578144,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581623680,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:3082",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581623680,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 876
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581648240,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:3053",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648240,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581916352,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:3039",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581916352,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582322880,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:3039",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582322880,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 798
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
int do_brk_flags(struct ma_state * mas, struct vm_area_struct * vma, long unsigned int addr, long unsigned int len, long unsigned int flags)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582820176,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:2945",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582820176,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
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
int do_brk_flags(struct vma_iterator * vmi, struct vm_area_struct * vma, long unsigned int addr, long unsigned int len, long unsigned int flags)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583034656,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:3042",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583034656,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
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
int do_brk_flags(struct vma_iterator * vmi, struct vm_area_struct * vma, long unsigned int addr, long unsigned int len, long unsigned int flags)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583216016,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:3131",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583216016,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492789072,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:3009",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__arm64_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492789072,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226604432,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:3009",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__se_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226604432,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 808
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286158624,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:3009",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__se_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286158624,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 964
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272759434,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:3009",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__se_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272759434,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581350864,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:3009",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581350864,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 833
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581294576,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:3009",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581294576,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 833
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581342064,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:3009",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581342064,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 833
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
int do_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags, struct list_head * uf)
```

```json
{
  "name": "do_brk_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581406000,
      "name": "do_brk_flags",
      "external": false,
      "loc": "mm/mmap.c:3009",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581406000,
      "name": "do_brk_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 833
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
int do_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags, struct list_head * uf)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int len</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int request</code>
</li>
</ul>
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
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ma_state * mas</code>
</li>
<li>
<b>Param added. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param removed. </b>
<code>struct list_head * uf</code>
</li>
<li>
<b>Param reordered. </b>
<code>addr, len, flags, uf</code> ➡️ <code>mas, vma, addr, len, flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vma_iterator * vmi</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ma_state * mas</code>
</li>
</ul>
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
