# Function: <code>ftrace_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ftrace_write(long unsigned int ip, const char * val, int size)
```

```json
{
  "name": "ftrace_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579216384,
      "name": "ftrace_write",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:299",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:add_break",
        "arch/x86/kernel/ftrace.c:update_ftrace_func",
        "arch/x86/kernel/ftrace.c:update_ftrace_func",
        "arch/x86/kernel/ftrace.c:update_ftrace_func",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579216384,
      "name": "ftrace_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int ftrace_write(long unsigned int ip, const char * val, int size)
```

```json
{
  "name": "ftrace_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579216992,
      "name": "ftrace_write",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:302",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:add_break",
        "arch/x86/kernel/ftrace.c:update_ftrace_func",
        "arch/x86/kernel/ftrace.c:update_ftrace_func",
        "arch/x86/kernel/ftrace.c:update_ftrace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579216992,
      "name": "ftrace_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int ftrace_write(long unsigned int ip, const char * val, int size)
```

```json
{
  "name": "ftrace_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579228832,
      "name": "ftrace_write",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:302",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:add_break",
        "arch/x86/kernel/ftrace.c:update_ftrace_func",
        "arch/x86/kernel/ftrace.c:update_ftrace_func",
        "arch/x86/kernel/ftrace.c:update_ftrace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579228832,
      "name": "ftrace_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int ftrace_write(long unsigned int ip, const char * val, int size)
```

```json
{
  "name": "ftrace_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579226464,
      "name": "ftrace_write",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:302",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:add_break",
        "arch/x86/kernel/ftrace.c:update_ftrace_func",
        "arch/x86/kernel/ftrace.c:update_ftrace_func",
        "arch/x86/kernel/ftrace.c:update_ftrace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579226464,
      "name": "ftrace_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int ftrace_write(long unsigned int ip, const char * val, int size)
```

```json
{
  "name": "ftrace_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579241984,
      "name": "ftrace_write",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:303",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:add_break",
        "arch/x86/kernel/ftrace.c:update_ftrace_func",
        "arch/x86/kernel/ftrace.c:update_ftrace_func",
        "arch/x86/kernel/ftrace.c:update_ftrace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579241984,
      "name": "ftrace_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int ftrace_write(long unsigned int ip, const char * val, int size)
```

```json
{
  "name": "ftrace_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579254560,
      "name": "ftrace_write",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:303",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:add_break",
        "arch/x86/kernel/ftrace.c:update_ftrace_func",
        "arch/x86/kernel/ftrace.c:update_ftrace_func",
        "arch/x86/kernel/ftrace.c:update_ftrace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579254560,
      "name": "ftrace_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int ftrace_write(long unsigned int ip, const char * val, int size)
```

```json
{
  "name": "ftrace_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579278288,
      "name": "ftrace_write",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:306",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:add_break"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579278288,
      "name": "ftrace_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int ftrace_write(long unsigned int ip, const char * val, int size)
```

```json
{
  "name": "ftrace_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579292800,
      "name": "ftrace_write",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:329",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:add_break"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579292800,
      "name": "ftrace_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int ftrace_write(long unsigned int ip, const char * val, int size)
```

```json
{
  "name": "ftrace_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579298432,
      "name": "ftrace_write",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:329",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:add_break"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579298432,
      "name": "ftrace_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
int ftrace_write(long unsigned int ip, const char * val, int size)
```

```json
{
  "name": "ftrace_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579294240,
      "name": "ftrace_write",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:329",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:add_break"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294240,
      "name": "ftrace_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int ftrace_write(long unsigned int ip, const char * val, int size)
```

```json
{
  "name": "ftrace_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579229760,
      "name": "ftrace_write",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:329",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:add_break"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229760,
      "name": "ftrace_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int ftrace_write(long unsigned int ip, const char * val, int size)
```

```json
{
  "name": "ftrace_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579295440,
      "name": "ftrace_write",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:329",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:add_break"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579295440,
      "name": "ftrace_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int ftrace_write(long unsigned int ip, const char * val, int size)
```

```json
{
  "name": "ftrace_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579304272,
      "name": "ftrace_write",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:329",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:add_break"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304272,
      "name": "ftrace_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int ftrace_write(long unsigned int ip, const char * val, int size)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int ftrace_write(long unsigned int ip, const char * val, int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int ftrace_write(long unsigned int ip, const char * val, int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int ftrace_write(long unsigned int ip, const char * val, int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int ftrace_write(long unsigned int ip, const char * val, int size)
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
