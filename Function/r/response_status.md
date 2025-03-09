# Function: <code>response_status</code>

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
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583427083,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:921",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583606987,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:933",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583823109,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:950",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583906197,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:950",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584090035,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:981",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584212747,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:980",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
u8 response_status(const struct parsed_resp * resp)
```

```json
{
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584597984,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:982",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:end_session_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584597984,
      "name": "response_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
u8 response_status(const struct parsed_resp * resp)
```

```json
{
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584716832,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:982",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:end_session_cont"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584716832,
      "name": "response_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584746554,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:982",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585174647,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:982",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585911703,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:982",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586701329,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:1022",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586962289,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:1030",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587242705,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:1147",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496083852,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:980",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229413700,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:980",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290324988,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:980",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275156408,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:980",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584181483,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:980",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584116731,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:980",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584165243,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:980",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
  "name": "response_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584269627,
      "name": "response_status",
      "external": false,
      "loc": "block/sed-opal.c:980",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:parse_and_check_status"
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
u8 response_status(const struct parsed_resp * resp)
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
u8 response_status(const struct parsed_resp * resp)
```
</details>
</li>
</ul>
