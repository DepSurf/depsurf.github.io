# Function: <code>parse_linerange</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int parse_linerange(struct ddebug_query * query, const char * first)
```

```json
{
  "name": "parse_linerange",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_linerange",
      "external": false,
      "loc": "lib/dynamic_debug.c:306",
      "file": "lib/dynamic_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dynamic_debug.c:ddebug_parse_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585115760,
      "name": "parse_linerange",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071591379525,
      "name": "parse_linerange.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int parse_linerange(struct ddebug_query * query, const char * first)
```

```json
{
  "name": "parse_linerange",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_linerange",
      "external": false,
      "loc": "lib/dynamic_debug.c:306",
      "file": "lib/dynamic_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dynamic_debug.c:ddebug_parse_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584996080,
      "name": "parse_linerange",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071591321879,
      "name": "parse_linerange.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int parse_linerange(struct ddebug_query * query, const char * first)
```

```json
{
  "name": "parse_linerange",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_linerange",
      "external": false,
      "loc": "lib/dynamic_debug.c:306",
      "file": "lib/dynamic_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dynamic_debug.c:ddebug_parse_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585435472,
      "name": "parse_linerange",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071592335424,
      "name": "parse_linerange.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int parse_linerange(struct ddebug_query * query, const char * first)
```

```json
{
  "name": "parse_linerange",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_linerange",
      "external": false,
      "loc": "lib/dynamic_debug.c:310",
      "file": "lib/dynamic_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dynamic_debug.c:ddebug_parse_query",
        "lib/dynamic_debug.c:ddebug_parse_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586577376,
      "name": "parse_linerange",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    },
    {
      "addr": 18446744071594196361,
      "name": "parse_linerange.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int parse_linerange(struct ddebug_query * query, const char * first)
```

```json
{
  "name": "parse_linerange",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587813536,
      "name": "parse_linerange",
      "external": false,
      "loc": "lib/dynamic_debug.c:348",
      "file": "lib/dynamic_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dynamic_debug.c:ddebug_parse_query",
        "lib/dynamic_debug.c:ddebug_parse_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587813536,
      "name": "parse_linerange",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
int parse_linerange(struct ddebug_query * query, const char * first)
```

```json
{
  "name": "parse_linerange",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588085264,
      "name": "parse_linerange",
      "external": false,
      "loc": "lib/dynamic_debug.c:348",
      "file": "lib/dynamic_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dynamic_debug.c:ddebug_parse_query",
        "lib/dynamic_debug.c:ddebug_parse_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588085264,
      "name": "parse_linerange",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
int parse_linerange(struct ddebug_query * query, const char * first)
```

```json
{
  "name": "parse_linerange",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588421104,
      "name": "parse_linerange",
      "external": false,
      "loc": "lib/dynamic_debug.c:349",
      "file": "lib/dynamic_debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dynamic_debug.c:ddebug_parse_query",
        "lib/dynamic_debug.c:ddebug_parse_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588421104,
      "name": "parse_linerange",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int parse_linerange(struct ddebug_query * query, const char * first)
```
</details>
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
