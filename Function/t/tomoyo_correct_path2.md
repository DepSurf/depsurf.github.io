# Function: <code>tomoyo_correct_path2</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool tomoyo_correct_path2(const char * filename, const size_t len)
```

```json
{
  "name": "tomoyo_correct_path2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584116768,
      "name": "tomoyo_correct_path2",
      "external": false,
      "loc": "security/tomoyo/util.c:531",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/util.c:tomoyo_correct_path",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584116768,
      "name": "tomoyo_correct_path2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
bool tomoyo_correct_path2(const char * filename, const size_t len)
```

```json
{
  "name": "tomoyo_correct_path2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584144304,
      "name": "tomoyo_correct_path2",
      "external": false,
      "loc": "security/tomoyo/util.c:531",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/util.c:tomoyo_correct_path",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584144304,
      "name": "tomoyo_correct_path2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
bool tomoyo_correct_path2(const char * filename, const size_t len)
```

```json
{
  "name": "tomoyo_correct_path2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584528128,
      "name": "tomoyo_correct_path2",
      "external": false,
      "loc": "security/tomoyo/util.c:531",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/util.c:tomoyo_correct_path",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584528128,
      "name": "tomoyo_correct_path2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
bool tomoyo_correct_path2(const char * filename, const size_t len)
```

```json
{
  "name": "tomoyo_correct_path2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585167664,
      "name": "tomoyo_correct_path2",
      "external": false,
      "loc": "security/tomoyo/util.c:531",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/util.c:tomoyo_correct_domain",
        "security/tomoyo/util.c:tomoyo_correct_path",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585167664,
      "name": "tomoyo_correct_path2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
bool tomoyo_correct_path2(const char * filename, const size_t len)
```

```json
{
  "name": "tomoyo_correct_path2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585894592,
      "name": "tomoyo_correct_path2",
      "external": false,
      "loc": "security/tomoyo/util.c:531",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/util.c:tomoyo_correct_domain",
        "security/tomoyo/util.c:tomoyo_correct_path",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585894592,
      "name": "tomoyo_correct_path2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
bool tomoyo_correct_path2(const char * filename, const size_t len)
```

```json
{
  "name": "tomoyo_correct_path2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586126448,
      "name": "tomoyo_correct_path2",
      "external": false,
      "loc": "security/tomoyo/util.c:531",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/util.c:tomoyo_correct_domain",
        "security/tomoyo/util.c:tomoyo_correct_path",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586126448,
      "name": "tomoyo_correct_path2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
bool tomoyo_correct_path2(const char * filename, const size_t len)
```

```json
{
  "name": "tomoyo_correct_path2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586375728,
      "name": "tomoyo_correct_path2",
      "external": false,
      "loc": "security/tomoyo/util.c:531",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/util.c:tomoyo_correct_domain",
        "security/tomoyo/util.c:tomoyo_correct_path",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586375728,
      "name": "tomoyo_correct_path2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
bool tomoyo_correct_path2(const char * filename, const size_t len)
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
