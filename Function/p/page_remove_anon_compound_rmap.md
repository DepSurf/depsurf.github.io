# Function: <code>page_remove_anon_compound_rmap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580844162,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1346",
      "file": "mm/rmap.c",
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
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580914690,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1345",
      "file": "mm/rmap.c",
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
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580958489,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1246",
      "file": "mm/rmap.c",
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
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581060233,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1250",
      "file": "mm/rmap.c",
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
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581199407,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1252",
      "file": "mm/rmap.c",
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
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581282756,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1254",
      "file": "mm/rmap.c",
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
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581357122,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1255",
      "file": "mm/rmap.c",
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
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581416722,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1257",
      "file": "mm/rmap.c",
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
void page_remove_anon_compound_rmap(struct page * page)
```

```json
{
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581615328,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1275",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_remove_rmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581615328,
      "name": "page_remove_anon_compound_rmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
void page_remove_anon_compound_rmap(struct page * page)
```

```json
{
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581660352,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1281",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_remove_rmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581660352,
      "name": "page_remove_anon_compound_rmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
void page_remove_anon_compound_rmap(struct page * page)
```

```json
{
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581682080,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1292",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_remove_rmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581682080,
      "name": "page_remove_anon_compound_rmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
void page_remove_anon_compound_rmap(struct page * page)
```

```json
{
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581951360,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1295",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_remove_rmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581951360,
      "name": "page_remove_anon_compound_rmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
void page_remove_anon_compound_rmap(struct page * page)
```

```json
{
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582368080,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1380",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_remove_rmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582368080,
      "name": "page_remove_anon_compound_rmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
    }
  ]
}
```
</details>
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
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492816624,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1257",
      "file": "mm/rmap.c",
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
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226624804,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1257",
      "file": "mm/rmap.c",
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
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286198820,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1257",
      "file": "mm/rmap.c",
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
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272775800,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1257",
      "file": "mm/rmap.c",
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
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581385570,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1257",
      "file": "mm/rmap.c",
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
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581328338,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1257",
      "file": "mm/rmap.c",
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
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581376770,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1257",
      "file": "mm/rmap.c",
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
  "name": "page_remove_anon_compound_rmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581440626,
      "name": "page_remove_anon_compound_rmap",
      "external": false,
      "loc": "mm/rmap.c:1257",
      "file": "mm/rmap.c",
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
void page_remove_anon_compound_rmap(struct page * page)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void page_remove_anon_compound_rmap(struct page * page)
```
</details>
</li>
</ul>
