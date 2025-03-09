# Function: <code>unlock_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int unlock_request(struct fuse_req * req)
```

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582045904,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:688",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_one",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582045904,
      "name": "unlock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int unlock_request(struct fuse_req * req)
```

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582259680,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:663",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_one",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582259680,
      "name": "unlock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int unlock_request(struct fuse_req * req)
```

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582349360,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:667",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_one",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349360,
      "name": "unlock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582438190,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:666",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435472,
      "name": "unlock_request.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582588333,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:666",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582585952,
      "name": "unlock_request.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582780934,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:679",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582778528,
      "name": "unlock_request.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582884198,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:733",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582882704,
      "name": "unlock_request.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583064861,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:757",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583061712,
      "name": "unlock_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583174269,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:623",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583168208,
      "name": "unlock_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583498009,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:623",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dev.c:fuse_copy_fill"
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
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583606730,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:636",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dev.c:fuse_copy_fill"
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
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583629977,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:636",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dev.c:fuse_copy_fill"
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
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583989038,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:636",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dev.c:fuse_copy_fill"
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
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584572001,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:628",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dev.c:fuse_copy_fill"
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
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585248104,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:628",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585241248,
      "name": "unlock_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585477848,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:630",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585471056,
      "name": "unlock_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585712872,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:630",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585706080,
      "name": "unlock_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494889836,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:623",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494881968,
      "name": "unlock_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228303836,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:623",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228296936,
      "name": "unlock_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288752392,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:623",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288748672,
      "name": "unlock_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274204844,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:623",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274198610,
      "name": "unlock_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583143005,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:623",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583136944,
      "name": "unlock_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583080157,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:623",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583074096,
      "name": "unlock_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583127037,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:623",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583120976,
      "name": "unlock_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583220637,
      "name": "unlock_request",
      "external": false,
      "loc": "fs/fuse/dev.c:623",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583215088,
      "name": "unlock_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int unlock_request(struct fuse_req * req)
```
</details>
</li>
</ul>
