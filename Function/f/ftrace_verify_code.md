# Function: <code>ftrace_verify_code</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ftrace_verify_code(long unsigned int ip, const char * old_code)
```

```json
{
  "name": "ftrace_verify_code",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579327600,
      "name": "ftrace_verify_code",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:77",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327600,
      "name": "ftrace_verify_code",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int ftrace_verify_code(long unsigned int ip, const char * old_code)
```

```json
{
  "name": "ftrace_verify_code",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579329152,
      "name": "ftrace_verify_code",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:77",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329152,
      "name": "ftrace_verify_code",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int ftrace_verify_code(long unsigned int ip, const char * old_code)
```

```json
{
  "name": "ftrace_verify_code",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579331856,
      "name": "ftrace_verify_code",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:77",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331856,
      "name": "ftrace_verify_code",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int ftrace_verify_code(long unsigned int ip, const char * old_code)
```

```json
{
  "name": "ftrace_verify_code",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579387120,
      "name": "ftrace_verify_code",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:77",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387120,
      "name": "ftrace_verify_code",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int ftrace_verify_code(long unsigned int ip, const char * old_code)
```

```json
{
  "name": "ftrace_verify_code",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579453072,
      "name": "ftrace_verify_code",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:75",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579453072,
      "name": "ftrace_verify_code",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int ftrace_verify_code(long unsigned int ip, const char * old_code)
```

```json
{
  "name": "ftrace_verify_code",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579541616,
      "name": "ftrace_verify_code",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:79",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541616,
      "name": "ftrace_verify_code",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int ftrace_verify_code(long unsigned int ip, const char * old_code)
```

```json
{
  "name": "ftrace_verify_code",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579554864,
      "name": "ftrace_verify_code",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:79",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554864,
      "name": "ftrace_verify_code",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int ftrace_verify_code(long unsigned int ip, const char * old_code)
```

```json
{
  "name": "ftrace_verify_code",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579582384,
      "name": "ftrace_verify_code",
      "external": false,
      "loc": "arch/x86/kernel/ftrace.c:79",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_replace_code",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579582384,
      "name": "ftrace_verify_code",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ftrace_verify_code(long unsigned int ip, const char * old_code)
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
