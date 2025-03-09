# Function: <code>save_microcode_in_initrd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595019898,
      "name": "save_microcode_in_initrd",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:185",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:free_initrd_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595019898,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595184526,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:177",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595184526,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595427274,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:192",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595427274,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596347944,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:221",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596347944,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 160
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
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602666042,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:238",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602666042,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 160
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
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602837324,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:238",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602837324,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 153
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
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604631310,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:238",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604631310,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 153
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
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604728539,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:234",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604728539,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 153
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
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604741652,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:234",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604741652,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 153
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
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609087936,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:229",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609087936,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 153
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
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612151699,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:227",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612151699,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 153
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
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614291317,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:227",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614291317,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 153
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
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615217368,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:227",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615217368,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 153
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
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616991033,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:210",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616991033,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 182
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
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627615696,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:210",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627615696,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 186
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
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619371296,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:210",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619371296,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 193
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
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621667456,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:519",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621667456,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 288
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604667955,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:234",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604667955,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 153
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
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604635080,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:234",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604635080,
      "name": "save_microcode_in_initrd",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604745718,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:234",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604745718,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 153
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
int save_microcode_in_initrd()
```

```json
{
  "name": "save_microcode_in_initrd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604745764,
      "name": "save_microcode_in_initrd",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:234",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604745764,
      "name": "save_microcode_in_initrd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 153
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int save_microcode_in_initrd()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int save_microcode_in_initrd()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int save_microcode_in_initrd()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int save_microcode_in_initrd()
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
