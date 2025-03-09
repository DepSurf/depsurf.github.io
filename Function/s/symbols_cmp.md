# Function: <code>symbols_cmp</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int symbols_cmp(const void * a, const void * b)
```

```json
{
  "name": "symbols_cmp",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580980048,
      "name": "symbols_cmp",
      "external": false,
      "loc": "kernel/trace/ftrace.c:8023",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581369488,
      "name": "symbols_cmp",
      "external": false,
      "loc": "kernel/trace/fprobe.c:88",
      "file": "kernel/trace/fprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980048,
      "name": "symbols_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581369488,
      "name": "symbols_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int symbols_cmp(const void * a, const void * b)
```

```json
{
  "name": "symbols_cmp",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276608,
      "name": "symbols_cmp",
      "external": false,
      "loc": "kernel/trace/ftrace.c:8276",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581705872,
      "name": "symbols_cmp",
      "external": false,
      "loc": "kernel/trace/fprobe.c:88",
      "file": "kernel/trace/fprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276608,
      "name": "symbols_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581705872,
      "name": "symbols_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
int symbols_cmp(const void * a, const void * b)
```

```json
{
  "name": "symbols_cmp",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581371872,
      "name": "symbols_cmp",
      "external": false,
      "loc": "kernel/trace/ftrace.c:8091",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581850784,
      "name": "symbols_cmp",
      "external": false,
      "loc": "kernel/trace/fprobe.c:150",
      "file": "kernel/trace/fprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371872,
      "name": "symbols_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581850784,
      "name": "symbols_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
int symbols_cmp(const void * a, const void * b)
```

```json
{
  "name": "symbols_cmp",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581478672,
      "name": "symbols_cmp",
      "external": false,
      "loc": "kernel/trace/ftrace.c:8091",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581973904,
      "name": "symbols_cmp",
      "external": false,
      "loc": "kernel/trace/fprobe.c:150",
      "file": "kernel/trace/fprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581478672,
      "name": "symbols_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581973904,
      "name": "symbols_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int symbols_cmp(const void * a, const void * b)
```
</details>
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
