# Function: <code>parse_crashkernel_suffix</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595102542,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/kexec_core.c:1175",
      "file": "kernel/kexec_core.c",
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
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595271405,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/kexec_core.c:1222",
      "file": "kernel/kexec_core.c",
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
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595517177,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/kexec_core.c:1224",
      "file": "kernel/kexec_core.c",
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
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596436128,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:161",
      "file": "kernel/crash_core.c",
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
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602761941,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:162",
      "file": "kernel/crash_core.c",
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
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602935790,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:162",
      "file": "kernel/crash_core.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604733635,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:162",
      "file": "kernel/crash_core.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604834935,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:160",
      "file": "kernel/crash_core.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604869077,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:160",
      "file": "kernel/crash_core.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int parse_crashkernel_suffix(char * cmdline, long long unsigned int * crash_size, const char * suffix)
```

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609197328,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:160",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609197328,
      "name": "parse_crashkernel_suffix",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 199
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
int parse_crashkernel_suffix(char * cmdline, long long unsigned int * crash_size, const char * suffix)
```

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612263840,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:162",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612263840,
      "name": "parse_crashkernel_suffix",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 199
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
int parse_crashkernel_suffix(char * cmdline, long long unsigned int * crash_size, const char * suffix)
```

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614404786,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:162",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614404786,
      "name": "parse_crashkernel_suffix",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 199
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
int parse_crashkernel_suffix(char * cmdline, long long unsigned int * crash_size, const char * suffix)
```

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615340263,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:164",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615340263,
      "name": "parse_crashkernel_suffix",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 199
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
int parse_crashkernel_suffix(char * cmdline, long long unsigned int * crash_size, const char * suffix)
```

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617125332,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:164",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617125332,
      "name": "parse_crashkernel_suffix",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 189
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
int parse_crashkernel_suffix(char * cmdline, long long unsigned int * crash_size, const char * suffix)
```

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627796336,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:176",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627796336,
      "name": "parse_crashkernel_suffix",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 205
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
int parse_crashkernel_suffix(char * cmdline, long long unsigned int * crash_size, const char * suffix)
```

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619559360,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:176",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619559360,
      "name": "parse_crashkernel_suffix",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 205
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
int parse_crashkernel_suffix(char * cmdline, long long unsigned int * crash_size, const char * suffix)
```

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621861280,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:200",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:__parse_crashkernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621861280,
      "name": "parse_crashkernel_suffix",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 205
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
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510905360,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:160",
      "file": "kernel/crash_core.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243392612,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:160",
      "file": "kernel/crash_core.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302541496,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:160",
      "file": "kernel/crash_core.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270643130,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:160",
      "file": "kernel/crash_core.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604774534,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:160",
      "file": "kernel/crash_core.c",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604743449,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:160",
      "file": "kernel/crash_core.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604851721,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:160",
      "file": "kernel/crash_core.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604873219,
      "name": "parse_crashkernel_suffix",
      "external": false,
      "loc": "kernel/crash_core.c:160",
      "file": "kernel/crash_core.c",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int parse_crashkernel_suffix(char * cmdline, long long unsigned int * crash_size, const char * suffix)
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
