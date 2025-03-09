# Function: <code>write_ok_or_segv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool write_ok_or_segv(long unsigned int ptr, size_t size)
```

```json
{
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578863088,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:95",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578863088,
      "name": "write_ok_or_segv.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071578863248,
      "name": "write_ok_or_segv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578863910,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:95",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578863424,
      "name": "write_ok_or_segv.part.3",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578864038,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:95",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578863552,
      "name": "write_ok_or_segv.part.3",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578863657,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:97",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578863168,
      "name": "write_ok_or_segv.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578864271,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:99",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578863792,
      "name": "write_ok_or_segv.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578866135,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:95",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578865712,
      "name": "write_ok_or_segv.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578865879,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:95",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578865552,
      "name": "write_ok_or_segv.part.7",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578866653,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:99",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578865744,
      "name": "write_ok_or_segv.part.0",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578866781,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:99",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578865872,
      "name": "write_ok_or_segv.part.0",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578870516,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:99",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool write_ok_or_segv(long unsigned int ptr, size_t size)
```

```json
{
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578866080,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:99",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578866080,
      "name": "write_ok_or_segv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578866256,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:99",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578867810,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:99",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578864183,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:99",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
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
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578866855,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:99",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
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
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578864861,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:99",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
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
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578875373,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:99",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578866781,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:99",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578865872,
      "name": "write_ok_or_segv.part.0",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578860349,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:99",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578859440,
      "name": "write_ok_or_segv.part.0",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578866717,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:99",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578865808,
      "name": "write_ok_or_segv.part.0",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_ok_or_segv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578867039,
      "name": "write_ok_or_segv",
      "external": false,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:99",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578866128,
      "name": "write_ok_or_segv.part.0",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
bool write_ok_or_segv(long unsigned int ptr, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool write_ok_or_segv(long unsigned int ptr, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool write_ok_or_segv(long unsigned int ptr, size_t size)
```
</details>
</li>
</ul>
