# Function: <code>add_to_platform_keyring</code>

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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604860575,
      "name": "add_to_platform_keyring",
      "external": false,
      "loc": "security/integrity/integrity.h:240",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604860575,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604965892,
      "name": "add_to_platform_keyring",
      "external": true,
      "loc": "security/integrity/platform_certs/platform_keyring.c:26",
      "file": "security/integrity/platform_certs/platform_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604965892,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605001713,
      "name": "add_to_platform_keyring",
      "external": true,
      "loc": "security/integrity/platform_certs/platform_keyring.c:26",
      "file": "security/integrity/platform_certs/platform_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605001713,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609282120,
      "name": "add_to_platform_keyring",
      "external": true,
      "loc": "security/integrity/platform_certs/platform_keyring.c:26",
      "file": "security/integrity/platform_certs/platform_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609282120,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612351093,
      "name": "add_to_platform_keyring",
      "external": true,
      "loc": "security/integrity/platform_certs/platform_keyring.c:26",
      "file": "security/integrity/platform_certs/platform_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612351093,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614492214,
      "name": "add_to_platform_keyring",
      "external": true,
      "loc": "security/integrity/platform_certs/platform_keyring.c:26",
      "file": "security/integrity/platform_certs/platform_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614492214,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615439400,
      "name": "add_to_platform_keyring",
      "external": true,
      "loc": "security/integrity/platform_certs/platform_keyring.c:26",
      "file": "security/integrity/platform_certs/platform_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615439400,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617237261,
      "name": "add_to_platform_keyring",
      "external": true,
      "loc": "security/integrity/platform_certs/platform_keyring.c:26",
      "file": "security/integrity/platform_certs/platform_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617237261,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627951008,
      "name": "add_to_platform_keyring",
      "external": true,
      "loc": "security/integrity/platform_certs/platform_keyring.c:26",
      "file": "security/integrity/platform_certs/platform_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627951008,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619714304,
      "name": "add_to_platform_keyring",
      "external": true,
      "loc": "security/integrity/platform_certs/platform_keyring.c:26",
      "file": "security/integrity/platform_certs/platform_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619714304,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622021552,
      "name": "add_to_platform_keyring",
      "external": true,
      "loc": "security/integrity/platform_certs/platform_keyring.c:26",
      "file": "security/integrity/platform_certs/platform_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622021552,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511046012,
      "name": "add_to_platform_keyring",
      "external": true,
      "loc": "security/integrity/platform_certs/platform_keyring.c:26",
      "file": "security/integrity/platform_certs/platform_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511046012,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243527696,
      "name": "add_to_platform_keyring",
      "external": true,
      "loc": "security/integrity/platform_certs/platform_keyring.c:26",
      "file": "security/integrity/platform_certs/platform_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3243527696,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302721364,
      "name": "add_to_platform_keyring",
      "external": true,
      "loc": "security/integrity/platform_certs/platform_keyring.c:26",
      "file": "security/integrity/platform_certs/platform_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302721364,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270758104,
      "name": "add_to_platform_keyring",
      "external": true,
      "loc": "security/integrity/platform_certs/platform_keyring.c:26",
      "file": "security/integrity/platform_certs/platform_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270758104,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604907173,
      "name": "add_to_platform_keyring",
      "external": true,
      "loc": "security/integrity/platform_certs/platform_keyring.c:26",
      "file": "security/integrity/platform_certs/platform_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604907173,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604876225,
      "name": "add_to_platform_keyring",
      "external": true,
      "loc": "security/integrity/platform_certs/platform_keyring.c:26",
      "file": "security/integrity/platform_certs/platform_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604876225,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604984345,
      "name": "add_to_platform_keyring",
      "external": true,
      "loc": "security/integrity/platform_certs/platform_keyring.c:26",
      "file": "security/integrity/platform_certs/platform_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604984345,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```

```json
{
  "name": "add_to_platform_keyring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605005883,
      "name": "add_to_platform_keyring",
      "external": true,
      "loc": "security/integrity/platform_certs/platform_keyring.c:26",
      "file": "security/integrity/platform_certs/platform_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605005883,
      "name": "add_to_platform_keyring",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void add_to_platform_keyring(const char * source, const void * data, size_t len)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
