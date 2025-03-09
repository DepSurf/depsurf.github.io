# Function: <code>unlazy_child</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unlazy_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581327165,
      "name": "unlazy_child",
      "external": false,
      "loc": "fs/namei.c:726",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_fast"
      ],
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
  "name": "unlazy_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581467315,
      "name": "unlazy_child",
      "external": false,
      "loc": "fs/namei.c:727",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_fast"
      ],
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
  "name": "unlazy_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581624220,
      "name": "unlazy_child",
      "external": false,
      "loc": "fs/namei.c:711",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_fast"
      ],
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
  "name": "unlazy_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581710444,
      "name": "unlazy_child",
      "external": false,
      "loc": "fs/namei.c:711",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_fast"
      ],
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
  "name": "unlazy_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581828423,
      "name": "unlazy_child",
      "external": false,
      "loc": "fs/namei.c:709",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_fast"
      ],
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
  "name": "unlazy_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581900983,
      "name": "unlazy_child",
      "external": false,
      "loc": "fs/namei.c:710",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_fast"
      ],
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
int unlazy_child(struct nameidata * nd, struct dentry * dentry, unsigned int seq)
```

```json
{
  "name": "unlazy_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582126224,
      "name": "unlazy_child",
      "external": false,
      "loc": "fs/namei.c:720",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:step_into",
        "fs/namei.c:lookup_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126224,
      "name": "unlazy_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
int unlazy_child(struct nameidata * nd, struct dentry * dentry, unsigned int seq)
```

```json
{
  "name": "unlazy_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582172720,
      "name": "unlazy_child",
      "external": false,
      "loc": "fs/namei.c:720",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:step_into",
        "fs/namei.c:lookup_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582172720,
      "name": "unlazy_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "unlazy_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493380940,
      "name": "unlazy_child",
      "external": false,
      "loc": "fs/namei.c:710",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_fast"
      ],
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
  "name": "unlazy_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226969604,
      "name": "unlazy_child",
      "external": false,
      "loc": "fs/namei.c:710",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_fast"
      ],
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
  "name": "unlazy_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286935164,
      "name": "unlazy_child",
      "external": false,
      "loc": "fs/namei.c:710",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_fast"
      ],
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
  "name": "unlazy_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273097870,
      "name": "unlazy_child",
      "external": false,
      "loc": "fs/namei.c:710",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_fast"
      ],
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
  "name": "unlazy_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581869719,
      "name": "unlazy_child",
      "external": false,
      "loc": "fs/namei.c:710",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_fast"
      ],
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
  "name": "unlazy_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581807319,
      "name": "unlazy_child",
      "external": false,
      "loc": "fs/namei.c:710",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_fast"
      ],
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
  "name": "unlazy_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581861031,
      "name": "unlazy_child",
      "external": false,
      "loc": "fs/namei.c:710",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_fast"
      ],
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
  "name": "unlazy_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581932935,
      "name": "unlazy_child",
      "external": false,
      "loc": "fs/namei.c:710",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_fast"
      ],
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
int unlazy_child(struct nameidata * nd, struct dentry * dentry, unsigned int seq)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int unlazy_child(struct nameidata * nd, struct dentry * dentry, unsigned int seq)
```
</details>
</li>
</ul>
