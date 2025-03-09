# Function: <code>pointer_string</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
char * pointer_string(char * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588800000,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:1650",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588800000,
      "name": "pointer_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
char * pointer_string(char * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589178160,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:1361",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589178160,
      "name": "pointer_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
char * pointer_string(char * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589407648,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:617",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589407648,
      "name": "pointer_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589876182,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:671",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
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
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590102086,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:671",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
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
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585104716,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:693",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
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
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585253900,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:696",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
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
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585137210,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:722",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
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
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585587548,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:723",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
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
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586743321,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:728",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:default_pointer",
        "lib/vsprintf.c:default_pointer"
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
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595906918,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:729",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:default_pointer",
        "lib/vsprintf.c:default_pointer"
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
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596425141,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:729",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:default_pointer",
        "lib/vsprintf.c:default_pointer"
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
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597320501,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:731",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:default_pointer",
        "lib/vsprintf.c:default_pointer"
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
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503879956,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:671",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
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
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236511868,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:671",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
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
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297748096,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:671",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
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
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279775708,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:671",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
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
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589704342,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:671",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
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
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589430134,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:671",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
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
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590147718,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:671",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
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
  "name": "pointer_string",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590198118,
      "name": "pointer_string",
      "external": false,
      "loc": "lib/vsprintf.c:671",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:restricted_pointer",
        "lib/vsprintf.c:ptr_to_id",
        "lib/vsprintf.c:ptr_to_id"
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
char * pointer_string(char * buf, char * end, const void * ptr, struct printf_spec spec)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
char * pointer_string(char * buf, char * end, const void * ptr, struct printf_spec spec)
```
</details>
</li>
</ul>
