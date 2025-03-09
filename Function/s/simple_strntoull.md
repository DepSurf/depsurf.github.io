# Function: <code>simple_strntoull</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long long unsigned int simple_strntoull(const char * startp, size_t max_chars, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strntoull",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585124814,
      "name": "simple_strntoull",
      "external": false,
      "loc": "lib/vsprintf.c:56",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:simple_strtoll"
      ],
      "caller_func": [
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:simple_strtoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585119760,
      "name": "simple_strntoull",
      "section": ".text",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
long long unsigned int simple_strntoull(const char * startp, size_t max_chars, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strntoull",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585574382,
      "name": "simple_strntoull",
      "external": false,
      "loc": "lib/vsprintf.c:56",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:simple_strtoll",
        "lib/vsprintf.c:simple_strtoull"
      ],
      "caller_func": [
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:simple_strtoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585569088,
      "name": "simple_strntoull",
      "section": ".text",
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
long long unsigned int simple_strntoull(const char * startp, size_t max_chars, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strntoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586722960,
      "name": "simple_strntoull",
      "external": false,
      "loc": "lib/vsprintf.c:61",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:simple_strtoll",
        "lib/vsprintf.c:simple_strtoll",
        "lib/vsprintf.c:simple_strtoull"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586722960,
      "name": "simple_strntoull",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long long unsigned int simple_strntoull(const char * startp, size_t max_chars, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strntoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595885712,
      "name": "simple_strntoull",
      "external": false,
      "loc": "lib/vsprintf.c:62",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:simple_strtoll",
        "lib/vsprintf.c:simple_strtoll",
        "lib/vsprintf.c:simple_strtoull"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595885712,
      "name": "simple_strntoull",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long long unsigned int simple_strntoull(const char * startp, size_t max_chars, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strntoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596403088,
      "name": "simple_strntoull",
      "external": false,
      "loc": "lib/vsprintf.c:62",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:simple_strtoll",
        "lib/vsprintf.c:simple_strtoll",
        "lib/vsprintf.c:simple_strtoull"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596403088,
      "name": "simple_strntoull",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long long unsigned int simple_strntoull(const char * startp, char * * endp, unsigned int base, size_t max_chars)
```

```json
{
  "name": "simple_strntoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597298192,
      "name": "simple_strntoull",
      "external": false,
      "loc": "lib/vsprintf.c:64",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:simple_strntoll",
        "lib/vsprintf.c:simple_strntoll",
        "lib/vsprintf.c:simple_strtoull"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597298192,
      "name": "simple_strntoull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
long long unsigned int simple_strntoull(const char * startp, size_t max_chars, char * * endp, unsigned int base)
```
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param reordered. </b>
<code>startp, max_chars, endp, base</code> ➡️ <code>startp, endp, base, max_chars</code>
</li>
</ul>
</details>
</li>
</ul>
