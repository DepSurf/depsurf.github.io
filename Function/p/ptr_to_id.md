# Function: <code>ptr_to_id</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588811029,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:1698",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer"
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
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589188013,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:1693",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:pointer"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
char * ptr_to_id(char * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589413936,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:688",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:pointer",
        "lib/vsprintf.c:time_and_date",
        "lib/vsprintf.c:netdev_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589413936,
      "name": "ptr_to_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
char * ptr_to_id(char * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589870400,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:743",
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
      "addr": 18446744071589870400,
      "name": "ptr_to_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
char * ptr_to_id(char * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590096304,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:743",
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
      "addr": 18446744071590096304,
      "name": "ptr_to_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
char * ptr_to_id(char * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585098176,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:791",
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
      "addr": 18446744071585098176,
      "name": "ptr_to_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
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
char * ptr_to_id(char * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585249760,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:794",
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
      "addr": 18446744071585249760,
      "name": "ptr_to_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
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
char * ptr_to_id(char * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585133184,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:820",
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
      "addr": 18446744071585133184,
      "name": "ptr_to_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
char * ptr_to_id(char * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585583088,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:821",
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
      "addr": 18446744071585583088,
      "name": "ptr_to_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586739074,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:804",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595902247,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:805",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596419876,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:805",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597315236,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:807",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
char * ptr_to_id(char * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503876448,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:743",
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
      "addr": 18446603336503876448,
      "name": "ptr_to_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
char * ptr_to_id(char * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236506924,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:743",
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
      "addr": 3236506924,
      "name": "ptr_to_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
char * ptr_to_id(char * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297740624,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:743",
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
      "addr": 13835058055297740624,
      "name": "ptr_to_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
char * ptr_to_id(char * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279770786,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:743",
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
      "addr": 18446743936279770786,
      "name": "ptr_to_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
char * ptr_to_id(char * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589698560,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:743",
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
      "addr": 18446744071589698560,
      "name": "ptr_to_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
char * ptr_to_id(char * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589424352,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:743",
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
      "addr": 18446744071589424352,
      "name": "ptr_to_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
char * ptr_to_id(char * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590141936,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:743",
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
      "addr": 18446744071590141936,
      "name": "ptr_to_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
char * ptr_to_id(char * buf, char * end, const void * ptr, struct printf_spec spec)
```

```json
{
  "name": "ptr_to_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590192336,
      "name": "ptr_to_id",
      "external": false,
      "loc": "lib/vsprintf.c:743",
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
      "addr": 18446744071590192336,
      "name": "ptr_to_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
char * ptr_to_id(char * buf, char * end, const void * ptr, struct printf_spec spec)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
char * ptr_to_id(char * buf, char * end, const void * ptr, struct printf_spec spec)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
