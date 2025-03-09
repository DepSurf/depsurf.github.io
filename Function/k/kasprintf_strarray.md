# Function: <code>kasprintf_strarray</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
char * * kasprintf_strarray(gfp_t gfp, const char * prefix, size_t n)
```

```json
{
  "name": "kasprintf_strarray",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586107024,
      "name": "kasprintf_strarray",
      "external": true,
      "loc": "lib/string_helpers.c:690",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/string_helpers.c:devm_kasprintf_strarray"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586107024,
      "name": "kasprintf_strarray",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
char * * kasprintf_strarray(gfp_t gfp, const char * prefix, size_t n)
```

```json
{
  "name": "kasprintf_strarray",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587092640,
      "name": "kasprintf_strarray",
      "external": true,
      "loc": "lib/string_helpers.c:734",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/string_helpers.c:devm_kasprintf_strarray"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587092640,
      "name": "kasprintf_strarray",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
char * * kasprintf_strarray(gfp_t gfp, const char * prefix, size_t n)
```

```json
{
  "name": "kasprintf_strarray",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587352752,
      "name": "kasprintf_strarray",
      "external": true,
      "loc": "lib/string_helpers.c:734",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/string_helpers.c:devm_kasprintf_strarray"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587352752,
      "name": "kasprintf_strarray",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
char * * kasprintf_strarray(gfp_t gfp, const char * prefix, size_t n)
```

```json
{
  "name": "kasprintf_strarray",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587639072,
      "name": "kasprintf_strarray",
      "external": true,
      "loc": "lib/string_helpers.c:751",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/string_helpers.c:devm_kasprintf_strarray"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639072,
      "name": "kasprintf_strarray",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
char * * kasprintf_strarray(gfp_t gfp, const char * prefix, size_t n)
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
