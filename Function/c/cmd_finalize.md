# Function: <code>cmd_finalize</code>

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
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583412698,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:638",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:finalize_and_send"
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
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583592362,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:650",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:finalize_and_send"
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
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583809297,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:647",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:finalize_and_send"
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
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583892177,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:647",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:finalize_and_send"
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
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584082685,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:682",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:finalize_and_send"
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
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584205389,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:684",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:finalize_and_send"
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
int cmd_finalize(struct opal_dev * cmd, u32 hsn, u32 tsn)
```

```json
{
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584601392,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:686",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:finalize_and_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584601392,
      "name": "cmd_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int cmd_finalize(struct opal_dev * cmd, u32 hsn, u32 tsn)
```

```json
{
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584720240,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:686",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:finalize_and_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584720240,
      "name": "cmd_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int cmd_finalize(struct opal_dev * cmd, u32 hsn, u32 tsn)
```

```json
{
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584747616,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:686",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:finalize_and_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584747616,
      "name": "cmd_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int cmd_finalize(struct opal_dev * cmd, u32 hsn, u32 tsn)
```

```json
{
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585175344,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:686",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:finalize_and_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585175344,
      "name": "cmd_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
int cmd_finalize(struct opal_dev * cmd, u32 hsn, u32 tsn)
```

```json
{
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585912624,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:686",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:finalize_and_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585912624,
      "name": "cmd_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
int cmd_finalize(struct opal_dev * cmd, u32 hsn, u32 tsn)
```

```json
{
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586702336,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:726",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:finalize_and_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586702336,
      "name": "cmd_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
int cmd_finalize(struct opal_dev * cmd, u32 hsn, u32 tsn)
```

```json
{
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586963856,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:734",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:finalize_and_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586963856,
      "name": "cmd_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
int cmd_finalize(struct opal_dev * cmd, u32 hsn, u32 tsn)
```

```json
{
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587244208,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:847",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:finalize_and_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587244208,
      "name": "cmd_finalize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496076312,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:684",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:finalize_and_send"
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
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229405232,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:684",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:finalize_and_send"
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
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290315680,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:684",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:finalize_and_send"
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
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275146726,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:684",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:finalize_and_send"
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
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584174125,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:684",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:finalize_and_send"
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
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584109373,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:684",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:finalize_and_send"
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
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584157885,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:684",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:finalize_and_send"
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
  "name": "cmd_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584262269,
      "name": "cmd_finalize",
      "external": false,
      "loc": "block/sed-opal.c:684",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:finalize_and_send"
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
int cmd_finalize(struct opal_dev * cmd, u32 hsn, u32 tsn)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
