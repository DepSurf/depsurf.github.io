# Function: <code>rtc_str</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589418256,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1603",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589418256,
      "name": "rtc_str",
      "section": ".text",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589875520,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1737",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589875520,
      "name": "rtc_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590101424,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1746",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590101424,
      "name": "rtc_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585095168,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1793",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:time64_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585095168,
      "name": "rtc_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585244288,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1797",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:time64_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585244288,
      "name": "rtc_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585130000,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1859",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:time64_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585130000,
      "name": "rtc_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585580400,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1864",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:time64_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585580400,
      "name": "rtc_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586735904,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1852",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:time64_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586735904,
      "name": "rtc_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595898928,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1853",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:time64_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595898928,
      "name": "rtc_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596416432,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1853",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:time64_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596416432,
      "name": "rtc_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597311792,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1855",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:time64_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597311792,
      "name": "rtc_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503877200,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1746",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503877200,
      "name": "rtc_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236509960,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1746",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236509960,
      "name": "rtc_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297741792,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1746",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297741792,
      "name": "rtc_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279771530,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1746",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279771530,
      "name": "rtc_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589703680,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1746",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589703680,
      "name": "rtc_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589429472,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1746",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589429472,
      "name": "rtc_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590147056,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1746",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590147056,
      "name": "rtc_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, struct printf_spec spec, const char * fmt)
```

```json
{
  "name": "rtc_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590197456,
      "name": "rtc_str",
      "external": false,
      "loc": "lib/vsprintf.c:1746",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:time_and_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590197456,
      "name": "rtc_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
char * rtc_str(char * buf, char * end, const struct rtc_time * tm, const char * fmt)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct printf_spec spec</code>
</li>
<li>
<b>Param reordered. </b>
<code>buf, end, tm, fmt</code> ➡️ <code>buf, end, tm, spec, fmt</code>
</li>
</ul>
</details>
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
