# Function: <code>mpage_bio_submit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581259378,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:58",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:mpage_readpage"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct bio * mpage_bio_submit(int op, int op_flags, struct bio * bio)
```

```json
{
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581424768,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:59",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581424768,
      "name": "mpage_bio_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581508407,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:59",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581561175,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:60",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581705159,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:61",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581871917,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:61",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581957005,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:61",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582089675,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:61",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582167092,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:61",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582403812,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:61",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582456932,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:61",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582486319,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:61",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582800527,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:61",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583353189,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:60",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_read_folio",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583930187,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:60",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_read_folio",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493721192,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:61",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227247204,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:61",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287327052,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:61",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273332608,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:61",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582135828,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:61",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582073268,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:61",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582126308,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:61",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
  "name": "mpage_bio_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582199332,
      "name": "mpage_bio_submit",
      "external": false,
      "loc": "fs/mpage.c:61",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct bio * mpage_bio_submit(int op, int op_flags, struct bio * bio)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
struct bio * mpage_bio_submit(int op, int op_flags, struct bio * bio)
```
</details>
</li>
</ul>
