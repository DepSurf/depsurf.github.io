# Function: <code>fourcc_string</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
char * fourcc_string(char * buf, char * end, const u32 * fourcc, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "fourcc_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fourcc_string",
      "external": false,
      "loc": "lib/vsprintf.c:1763",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585131248,
      "name": "fourcc_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
    },
    {
      "addr": 18446744071591324861,
      "name": "fourcc_string.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
char * fourcc_string(char * buf, char * end, const u32 * fourcc, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "fourcc_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fourcc_string",
      "external": false,
      "loc": "lib/vsprintf.c:1768",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585581472,
      "name": "fourcc_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
    },
    {
      "addr": 18446744071592344465,
      "name": "fourcc_string.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
char * fourcc_string(char * buf, char * end, const u32 * fourcc, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "fourcc_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fourcc_string",
      "external": false,
      "loc": "lib/vsprintf.c:1754",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586736784,
      "name": "fourcc_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 670
    },
    {
      "addr": 18446744071594206026,
      "name": "fourcc_string.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
char * fourcc_string(char * buf, char * end, const u32 * fourcc, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "fourcc_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595899856,
      "name": "fourcc_string",
      "external": false,
      "loc": "lib/vsprintf.c:1755",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595899856,
      "name": "fourcc_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
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
char * fourcc_string(char * buf, char * end, const u32 * fourcc, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "fourcc_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596417360,
      "name": "fourcc_string",
      "external": false,
      "loc": "lib/vsprintf.c:1755",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596417360,
      "name": "fourcc_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 827
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
char * fourcc_string(char * buf, char * end, const u32 * fourcc, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "fourcc_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597312720,
      "name": "fourcc_string",
      "external": false,
      "loc": "lib/vsprintf.c:1757",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597312720,
      "name": "fourcc_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 827
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
char * fourcc_string(char * buf, char * end, const u32 * fourcc, struct printf_spec spec, const char * fmt)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
