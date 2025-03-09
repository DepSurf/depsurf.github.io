# Function: <code>__static_call_init</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__static_call_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581179339,
      "name": "__static_call_init",
      "external": false,
      "loc": "kernel/static_call.c:209",
      "file": "kernel/static_call.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/static_call.c:static_call_add_module",
        "kernel/static_call.c:static_call_init"
      ],
      "caller_func": [
        "kernel/static_call.c:static_call_add_module",
        "kernel/static_call.c:static_call_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581178576,
      "name": "__static_call_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
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
  "name": "__static_call_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581197641,
      "name": "__static_call_init",
      "external": false,
      "loc": "kernel/static_call.c:209",
      "file": "kernel/static_call.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/static_call.c:static_call_module_notify",
        "kernel/static_call.c:static_call_init"
      ],
      "caller_func": [
        "kernel/static_call.c:static_call_module_notify",
        "kernel/static_call.c:static_call_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581196816,
      "name": "__static_call_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__static_call_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581437993,
      "name": "__static_call_init",
      "external": false,
      "loc": "kernel/static_call.c:209",
      "file": "kernel/static_call.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/static_call.c:static_call_module_notify",
        "kernel/static_call.c:static_call_init"
      ],
      "caller_func": [
        "kernel/static_call.c:static_call_module_notify",
        "kernel/static_call.c:static_call_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581437168,
      "name": "__static_call_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
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
int __static_call_init(struct module * mod, struct static_call_site * start, struct static_call_site * stop)
```

```json
{
  "name": "__static_call_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581776736,
      "name": "__static_call_init",
      "external": false,
      "loc": "kernel/static_call_inline.c:209",
      "file": "kernel/static_call_inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/static_call_inline.c:static_call_module_notify",
        "kernel/static_call_inline.c:static_call_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581776736,
      "name": "__static_call_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 526
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
int __static_call_init(struct module * mod, struct static_call_site * start, struct static_call_site * stop)
```

```json
{
  "name": "__static_call_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582201088,
      "name": "__static_call_init",
      "external": false,
      "loc": "kernel/static_call_inline.c:220",
      "file": "kernel/static_call_inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/static_call_inline.c:static_call_module_notify",
        "kernel/static_call_inline.c:static_call_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582201088,
      "name": "__static_call_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 526
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
int __static_call_init(struct module * mod, struct static_call_site * start, struct static_call_site * stop)
```

```json
{
  "name": "__static_call_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582400976,
      "name": "__static_call_init",
      "external": false,
      "loc": "kernel/static_call_inline.c:220",
      "file": "kernel/static_call_inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/static_call_inline.c:static_call_module_notify",
        "kernel/static_call_inline.c:static_call_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582400976,
      "name": "__static_call_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
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
int __static_call_init(struct module * mod, struct static_call_site * start, struct static_call_site * stop)
```

```json
{
  "name": "__static_call_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582568608,
      "name": "__static_call_init",
      "external": false,
      "loc": "kernel/static_call_inline.c:220",
      "file": "kernel/static_call_inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/static_call_inline.c:static_call_module_notify",
        "kernel/static_call_inline.c:static_call_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582568608,
      "name": "__static_call_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int __static_call_init(struct module * mod, struct static_call_site * start, struct static_call_site * stop)
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
