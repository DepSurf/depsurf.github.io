# Function: <code>__set_personality_x32</code>

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
  "name": "__set_personality_x32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579017728,
      "name": "__set_personality_x32",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:542",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32"
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
  "name": "__set_personality_x32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579021261,
      "name": "__set_personality_x32",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:543",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32"
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
  "name": "__set_personality_x32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579025804,
      "name": "__set_personality_x32",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:567",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32"
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
  "name": "__set_personality_x32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579030076,
      "name": "__set_personality_x32",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:652",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32"
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
  "name": "__set_personality_x32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579038044,
      "name": "__set_personality_x32",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:643",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32"
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
  "name": "__set_personality_x32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579040444,
      "name": "__set_personality_x32",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:643",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32"
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
void __set_personality_x32()
```

```json
{
  "name": "__set_personality_x32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579050608,
      "name": "__set_personality_x32",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:554",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:set_personality_ia32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579050608,
      "name": "__set_personality_x32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_personality_x32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579053388,
      "name": "__set_personality_x32",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:657",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32"
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
  "name": "__set_personality_x32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579060316,
      "name": "__set_personality_x32",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:657",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32"
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
  "name": "__set_personality_x32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579081564,
      "name": "__set_personality_x32",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:683",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32"
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
  "name": "__set_personality_x32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_personality_x32",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:682",
      "file": "arch/x86/kernel/process_64.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_personality_x32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_personality_x32",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:683",
      "file": "arch/x86/kernel/process_64.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_personality_x32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_personality_x32",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:684",
      "file": "arch/x86/kernel/process_64.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_personality_x32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_personality_x32",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:686",
      "file": "arch/x86/kernel/process_64.c",
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
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
  "name": "__set_personality_x32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579040796,
      "name": "__set_personality_x32",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:643",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32"
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
  "name": "__set_personality_x32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578973756,
      "name": "__set_personality_x32",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:643",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32"
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
  "name": "__set_personality_x32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579040380,
      "name": "__set_personality_x32",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:643",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32"
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
  "name": "__set_personality_x32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579044044,
      "name": "__set_personality_x32",
      "external": false,
      "loc": "arch/x86/kernel/process_64.c:643",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32"
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
void __set_personality_x32()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void __set_personality_x32()
```
</details>
</li>
</ul>
