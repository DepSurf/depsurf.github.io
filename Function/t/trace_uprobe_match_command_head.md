# Function: <code>trace_uprobe_match_command_head</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_uprobe_match_command_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580778079,
      "name": "trace_uprobe_match_command_head",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:284",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
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
  "name": "trace_uprobe_match_command_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580899791,
      "name": "trace_uprobe_match_command_head",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:284",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
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
  "name": "trace_uprobe_match_command_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580894047,
      "name": "trace_uprobe_match_command_head",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:284",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
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
  "name": "trace_uprobe_match_command_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580897724,
      "name": "trace_uprobe_match_command_head",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:284",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
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
  "name": "trace_uprobe_match_command_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581102764,
      "name": "trace_uprobe_match_command_head",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:281",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
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
bool trace_uprobe_match_command_head(struct trace_uprobe * tu, int argc, const char * * argv)
```

```json
{
  "name": "trace_uprobe_match_command_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581356560,
      "name": "trace_uprobe_match_command_head",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:282",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356560,
      "name": "trace_uprobe_match_command_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
bool trace_uprobe_match_command_head(struct trace_uprobe * tu, int argc, const char * * argv)
```

```json
{
  "name": "trace_uprobe_match_command_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581691440,
      "name": "trace_uprobe_match_command_head",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:283",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581691440,
      "name": "trace_uprobe_match_command_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
bool trace_uprobe_match_command_head(struct trace_uprobe * tu, int argc, const char * * argv)
```

```json
{
  "name": "trace_uprobe_match_command_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581836416,
      "name": "trace_uprobe_match_command_head",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:281",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836416,
      "name": "trace_uprobe_match_command_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
bool trace_uprobe_match_command_head(struct trace_uprobe * tu, int argc, const char * * argv)
```

```json
{
  "name": "trace_uprobe_match_command_head",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581959888,
      "name": "trace_uprobe_match_command_head",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:276",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581959888,
      "name": "trace_uprobe_match_command_head",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
  "name": "trace_uprobe_match_command_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492089944,
      "name": "trace_uprobe_match_command_head",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:284",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
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
  "name": "trace_uprobe_match_command_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225994428,
      "name": "trace_uprobe_match_command_head",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:284",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
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
  "name": "trace_uprobe_match_command_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285288240,
      "name": "trace_uprobe_match_command_head",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:284",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
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
  "name": "trace_uprobe_match_command_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580746879,
      "name": "trace_uprobe_match_command_head",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:284",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
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
  "name": "trace_uprobe_match_command_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580693071,
      "name": "trace_uprobe_match_command_head",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:284",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
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
  "name": "trace_uprobe_match_command_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580738127,
      "name": "trace_uprobe_match_command_head",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:284",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
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
  "name": "trace_uprobe_match_command_head",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580796079,
      "name": "trace_uprobe_match_command_head",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:284",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool trace_uprobe_match_command_head(struct trace_uprobe * tu, int argc, const char * * argv)
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
