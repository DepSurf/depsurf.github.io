# Function: <code>edac_mc_scrub_block</code>

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
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586563453,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:831",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
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
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587030976,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:836",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
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
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587329075,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:838",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
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
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587507411,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:831",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
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
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587781286,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:827",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
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
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587985990,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:820",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
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
void edac_mc_scrub_block(long unsigned int page, long unsigned int offset, u32 size)
```

```json
{
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588838608,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:790",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_ce_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588838608,
      "name": "edac_mc_scrub_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void edac_mc_scrub_block(long unsigned int page, long unsigned int offset, u32 size)
```

```json
{
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588854784,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:794",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_ce_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588854784,
      "name": "edac_mc_scrub_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588743803,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:794",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_ce_error"
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
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589434267,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:797",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_ce_error"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void edac_mc_scrub_block(long unsigned int page, long unsigned int offset, u32 size)
```

```json
{
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590911808,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:722",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590911808,
      "name": "edac_mc_scrub_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void edac_mc_scrub_block(long unsigned int page, long unsigned int offset, u32 size)
```

```json
{
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592609664,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:721",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592609664,
      "name": "edac_mc_scrub_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void edac_mc_scrub_block(long unsigned int page, long unsigned int offset, u32 size)
```

```json
{
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593040224,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:721",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593040224,
      "name": "edac_mc_scrub_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
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
void edac_mc_scrub_block(long unsigned int page, long unsigned int offset, u32 size)
```

```json
{
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593791648,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:722",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593791648,
      "name": "edac_mc_scrub_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501231208,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:820",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
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
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233734256,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:820",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
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
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294759724,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:820",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
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
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277925652,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:820",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
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
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587616966,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:820",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
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
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587384982,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:820",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
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
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587942134,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:820",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
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
  "name": "edac_mc_scrub_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588057414,
      "name": "edac_mc_scrub_block",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:820",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
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
void edac_mc_scrub_block(long unsigned int page, long unsigned int offset, u32 size)
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
void edac_mc_scrub_block(long unsigned int page, long unsigned int offset, u32 size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void edac_mc_scrub_block(long unsigned int page, long unsigned int offset, u32 size)
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
