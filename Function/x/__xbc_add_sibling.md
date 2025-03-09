# Function: <code>__xbc_add_sibling</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xbc_node * __xbc_add_sibling(char * data, u32 flag, bool head)
```

```json
{
  "name": "__xbc_add_sibling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615452538,
      "name": "__xbc_add_sibling",
      "external": false,
      "loc": "lib/bootconfig.c:388",
      "file": "lib/bootconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bootconfig.c:xbc_add_child",
        "lib/bootconfig.c:xbc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615452538,
      "name": "__xbc_add_sibling",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 229
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
struct xbc_node * __xbc_add_sibling(char * data, uint32_t flag, bool head)
```

```json
{
  "name": "__xbc_add_sibling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617252956,
      "name": "__xbc_add_sibling",
      "external": false,
      "loc": "lib/bootconfig.c:453",
      "file": "lib/bootconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:xbc_add_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617252956,
      "name": "__xbc_add_sibling",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 246
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
struct xbc_node * __xbc_add_sibling(char * data, uint32_t flag, bool head)
```

```json
{
  "name": "__xbc_add_sibling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627971936,
      "name": "__xbc_add_sibling",
      "external": false,
      "loc": "lib/bootconfig.c:453",
      "file": "lib/bootconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:__xbc_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627971936,
      "name": "__xbc_add_sibling",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 291
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
struct xbc_node * __xbc_add_sibling(char * data, uint32_t flag, bool head)
```

```json
{
  "name": "__xbc_add_sibling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619737632,
      "name": "__xbc_add_sibling",
      "external": false,
      "loc": "lib/bootconfig.c:453",
      "file": "lib/bootconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bootconfig.c:xbc_parse_kv",
        "lib/bootconfig.c:xbc_parse_kv",
        "lib/bootconfig.c:__xbc_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619737632,
      "name": "__xbc_add_sibling",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 291
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
struct xbc_node * __xbc_add_sibling(char * data, uint32_t flag, bool head)
```

```json
{
  "name": "__xbc_add_sibling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622045792,
      "name": "__xbc_add_sibling",
      "external": false,
      "loc": "lib/bootconfig.c:453",
      "file": "lib/bootconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bootconfig.c:xbc_parse_kv",
        "lib/bootconfig.c:xbc_parse_kv",
        "lib/bootconfig.c:__xbc_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622045792,
      "name": "__xbc_add_sibling",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 291
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct xbc_node * __xbc_add_sibling(char * data, u32 flag, bool head)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 flag</code> ➡️ <code>uint32_t flag</code>
</li>
</ul>
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
