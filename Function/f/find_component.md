# Function: <code>find_component</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584707809,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:71",
      "file": "drivers/base/component.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584895025,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:71",
      "file": "drivers/base/component.c",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584980896,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:71",
      "file": "drivers/base/component.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585402128,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:71",
      "file": "drivers/base/component.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585644542,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:144",
      "file": "drivers/base/component.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585772990,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:134",
      "file": "drivers/base/component.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:try_to_bring_up_master"
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
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586005076,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:162",
      "file": "drivers/base/component.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:try_to_bring_up_master"
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
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586152212,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:162",
      "file": "drivers/base/component.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:try_to_bring_up_master"
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
struct component * find_component(struct master * master, struct component_match_array * mc)
```

```json
{
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586908288,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:161",
      "file": "drivers/base/component.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/component.c:find_components"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586908288,
      "name": "find_component",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct component * find_component(struct master * master, struct component_match_array * mc)
```

```json
{
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586992624,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:161",
      "file": "drivers/base/component.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/component.c:find_components"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586992624,
      "name": "find_component",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586875305,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:158",
      "file": "drivers/base/component.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:find_components"
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
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587436425,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:158",
      "file": "drivers/base/component.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:find_components"
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
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588752777,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:153",
      "file": "drivers/base/component.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:find_components"
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
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590240553,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:153",
      "file": "drivers/base/component.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:find_components"
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
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590560665,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:153",
      "file": "drivers/base/component.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:find_components"
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
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590918969,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:153",
      "file": "drivers/base/component.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:find_components"
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
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498944716,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:162",
      "file": "drivers/base/component.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:try_to_bring_up_master"
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
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231518624,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:162",
      "file": "drivers/base/component.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292086480,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:162",
      "file": "drivers/base/component.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276330180,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:162",
      "file": "drivers/base/component.c",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585912580,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:162",
      "file": "drivers/base/component.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:try_to_bring_up_master"
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
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585761716,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:162",
      "file": "drivers/base/component.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:try_to_bring_up_master"
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
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586102228,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:162",
      "file": "drivers/base/component.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:try_to_bring_up_master"
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
  "name": "find_component",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586210836,
      "name": "find_component",
      "external": false,
      "loc": "drivers/base/component.c:162",
      "file": "drivers/base/component.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/component.c:try_to_bring_up_master"
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
struct component * find_component(struct master * master, struct component_match_array * mc)
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
struct component * find_component(struct master * master, struct component_match_array * mc)
```
</details>
</li>
</ul>
