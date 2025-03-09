# Function: <code>unregister_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584488157,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:686",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:unregister_memory_section"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584834503,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:729",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:unregister_memory_section"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585027815,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:730",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:unregister_memory_section"
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
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585112439,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:727",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:unregister_memory_section"
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
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585538839,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:738",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:unregister_memory_section"
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
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585782498,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:746",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:unregister_memory_section"
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
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585915474,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:731",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:unregister_memory_section"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void unregister_memory(struct memory_block * memory)
```

```json
{
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586153776,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:705",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586153776,
      "name": "unregister_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void unregister_memory(struct memory_block * memory)
```

```json
{
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586302224,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:677",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586302224,
      "name": "unregister_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void unregister_memory(struct memory_block * memory)
```

```json
{
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587072544,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:618",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587072544,
      "name": "unregister_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void unregister_memory(struct memory_block * memory)
```

```json
{
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587156928,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:609",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587156928,
      "name": "unregister_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void unregister_memory(struct memory_block * memory)
```

```json
{
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587044432,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:677",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587044432,
      "name": "unregister_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void unregister_memory(struct memory_block * memory)
```

```json
{
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587613248,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:692",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587613248,
      "name": "unregister_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void unregister_memory(struct memory_block * memory)
```

```json
{
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499136088,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:677",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499136088,
      "name": "unregister_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void unregister_memory(struct memory_block * memory)
```

```json
{
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292326944,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:677",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292326944,
      "name": "unregister_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void unregister_memory(struct memory_block * memory)
```

```json
{
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586065472,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:677",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586065472,
      "name": "unregister_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void unregister_memory(struct memory_block * memory)
```

```json
{
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585911424,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:677",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585911424,
      "name": "unregister_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void unregister_memory(struct memory_block * memory)
```

```json
{
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586250192,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:677",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586250192,
      "name": "unregister_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void unregister_memory(struct memory_block * memory)
```

```json
{
  "name": "unregister_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586361136,
      "name": "unregister_memory",
      "external": false,
      "loc": "drivers/base/memory.c:677",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586361136,
      "name": "unregister_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void unregister_memory(struct memory_block * memory)
```
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void unregister_memory(struct memory_block * memory)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void unregister_memory(struct memory_block * memory)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void unregister_memory(struct memory_block * memory)
```
</details>
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
