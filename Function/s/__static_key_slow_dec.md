# Function: <code>__static_key_slow_dec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __static_key_slow_dec(struct static_key * key, long unsigned int rate_limit, struct delayed_work * work)
```

```json
{
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580462928,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:72",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:static_key_slow_dec_deferred",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580462928,
      "name": "__static_key_slow_dec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void __static_key_slow_dec(struct static_key * key, long unsigned int rate_limit, struct delayed_work * work)
```

```json
{
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580538384,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:139",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_deferred",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580538384,
      "name": "__static_key_slow_dec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void __static_key_slow_dec(struct static_key * key, long unsigned int rate_limit, struct delayed_work * work)
```

```json
{
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580602416,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:139",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_deferred",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602416,
      "name": "__static_key_slow_dec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __static_key_slow_dec(struct static_key * key, long unsigned int rate_limit, struct delayed_work * work)
```

```json
{
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580632256,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:142",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_deferred",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580632256,
      "name": "__static_key_slow_dec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580713948,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:209",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec_deferred",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580846060,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:210",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec_deferred",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580914876,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:233",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec_deferred",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581013063,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:252",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581069447,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:252",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581249175,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:252",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581291143,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:252",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581308807,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:252",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581553860,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:252",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581905575,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:252",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582339911,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:280",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582541879,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:280",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582711031,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:280",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492430388,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:252",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285698776,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:252",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581038295,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:252",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580984375,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:252",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581029495,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:252",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
  "name": "__static_key_slow_dec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581090919,
      "name": "__static_key_slow_dec",
      "external": false,
      "loc": "kernel/jump_label.c:252",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void __static_key_slow_dec(struct static_key * key, long unsigned int rate_limit, struct delayed_work * work)
```
</details>
</li>
</ul>
