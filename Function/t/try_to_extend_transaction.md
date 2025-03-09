# Function: <code>try_to_extend_transaction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int try_to_extend_transaction(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "try_to_extend_transaction",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581829136,
      "name": "try_to_extend_transaction",
      "external": false,
      "loc": "fs/ext4/indirect.c:815",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581829136,
      "name": "try_to_extend_transaction",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int try_to_extend_transaction(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "try_to_extend_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582025120,
      "name": "try_to_extend_transaction",
      "external": false,
      "loc": "fs/ext4/indirect.c:703",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582025120,
      "name": "try_to_extend_transaction",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int try_to_extend_transaction(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "try_to_extend_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582115216,
      "name": "try_to_extend_transaction",
      "external": false,
      "loc": "fs/ext4/indirect.c:703",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582115216,
      "name": "try_to_extend_transaction",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "try_to_extend_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581955887,
      "name": "try_to_extend_transaction",
      "external": false,
      "loc": "fs/ext4/indirect.c:703",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks"
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
  "name": "try_to_extend_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582104943,
      "name": "try_to_extend_transaction",
      "external": false,
      "loc": "fs/ext4/indirect.c:704",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks"
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
  "name": "try_to_extend_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582293101,
      "name": "try_to_extend_transaction",
      "external": false,
      "loc": "fs/ext4/indirect.c:710",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks"
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
  "name": "try_to_extend_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582391853,
      "name": "try_to_extend_transaction",
      "external": false,
      "loc": "fs/ext4/indirect.c:710",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks"
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
  "name": "try_to_extend_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582560702,
      "name": "try_to_extend_transaction",
      "external": false,
      "loc": "fs/ext4/indirect.c:704",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks"
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
  "name": "try_to_extend_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582661646,
      "name": "try_to_extend_transaction",
      "external": false,
      "loc": "fs/ext4/indirect.c:704",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks"
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
  "name": "try_to_extend_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494314140,
      "name": "try_to_extend_transaction",
      "external": false,
      "loc": "fs/ext4/indirect.c:704",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks"
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
  "name": "try_to_extend_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227749896,
      "name": "try_to_extend_transaction",
      "external": false,
      "loc": "fs/ext4/indirect.c:704",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks"
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
  "name": "try_to_extend_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288034428,
      "name": "try_to_extend_transaction",
      "external": false,
      "loc": "fs/ext4/indirect.c:704",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks"
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
  "name": "try_to_extend_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273753760,
      "name": "try_to_extend_transaction",
      "external": false,
      "loc": "fs/ext4/indirect.c:704",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks"
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
  "name": "try_to_extend_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582630382,
      "name": "try_to_extend_transaction",
      "external": false,
      "loc": "fs/ext4/indirect.c:704",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks"
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
  "name": "try_to_extend_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582567550,
      "name": "try_to_extend_transaction",
      "external": false,
      "loc": "fs/ext4/indirect.c:704",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks"
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
  "name": "try_to_extend_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582620238,
      "name": "try_to_extend_transaction",
      "external": false,
      "loc": "fs/ext4/indirect.c:704",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks"
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
  "name": "try_to_extend_transaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582702398,
      "name": "try_to_extend_transaction",
      "external": false,
      "loc": "fs/ext4/indirect.c:704",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int try_to_extend_transaction(handle_t * handle, struct inode * inode)
```
</details>
</li>
</ul>
