# Function: <code>msg_add_ext_text</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t msg_add_ext_text(char * buf, size_t size, const char * text, size_t text_len, unsigned char endc)
```

```json
{
  "name": "msg_add_ext_text",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579994499,
      "name": "msg_add_ext_text",
      "external": false,
      "loc": "kernel/printk/printk.c:564",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:msg_add_dict_text"
      ],
      "caller_func": [
        "kernel/printk/printk.c:msg_print_ext_body",
        "kernel/printk/printk.c:msg_add_dict_text",
        "kernel/printk/printk.c:msg_add_dict_text"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991424,
      "name": "msg_add_ext_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t msg_add_ext_text(char * buf, size_t size, const char * text, size_t text_len, unsigned char endc)
```

```json
{
  "name": "msg_add_ext_text",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579996179,
      "name": "msg_add_ext_text",
      "external": false,
      "loc": "kernel/printk/printk.c:577",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:msg_add_dict_text"
      ],
      "caller_func": [
        "kernel/printk/printk.c:msg_print_ext_body",
        "kernel/printk/printk.c:msg_add_dict_text",
        "kernel/printk/printk.c:msg_add_dict_text"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993168,
      "name": "msg_add_ext_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t msg_add_ext_text(char * buf, size_t size, const char * text, size_t text_len, unsigned char endc)
```

```json
{
  "name": "msg_add_ext_text",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580132051,
      "name": "msg_add_ext_text",
      "external": false,
      "loc": "kernel/printk/printk.c:572",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:msg_add_dict_text"
      ],
      "caller_func": [
        "kernel/printk/printk.c:msg_print_ext_body",
        "kernel/printk/printk.c:msg_add_dict_text",
        "kernel/printk/printk.c:msg_add_dict_text"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580125136,
      "name": "msg_add_ext_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t msg_add_ext_text(char * buf, size_t size, const char * text, size_t text_len, unsigned char endc)
```

```json
{
  "name": "msg_add_ext_text",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580273362,
      "name": "msg_add_ext_text",
      "external": false,
      "loc": "kernel/printk/printk.c:577",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:msg_add_dict_text"
      ],
      "caller_func": [
        "kernel/printk/printk.c:msg_print_ext_body",
        "kernel/printk/printk.c:msg_add_dict_text",
        "kernel/printk/printk.c:msg_add_dict_text"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580266944,
      "name": "msg_add_ext_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t msg_add_ext_text(char * buf, size_t size, const char * text, size_t text_len, unsigned char endc)
```

```json
{
  "name": "msg_add_ext_text",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580480994,
      "name": "msg_add_ext_text",
      "external": false,
      "loc": "kernel/printk/printk.c:658",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:msg_add_dict_text"
      ],
      "caller_func": [
        "kernel/printk/printk.c:msg_print_ext_body",
        "kernel/printk/printk.c:msg_add_dict_text",
        "kernel/printk/printk.c:msg_add_dict_text"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580472752,
      "name": "msg_add_ext_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t msg_add_ext_text(char * buf, size_t size, const char * text, size_t text_len, unsigned char endc)
```

```json
{
  "name": "msg_add_ext_text",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580552834,
      "name": "msg_add_ext_text",
      "external": false,
      "loc": "kernel/printk/printk.c:645",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:msg_add_dict_text"
      ],
      "caller_func": [
        "kernel/printk/printk.c:printk_get_next_message",
        "kernel/printk/printk.c:msg_add_dict_text",
        "kernel/printk/printk.c:msg_add_dict_text"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580544336,
      "name": "msg_add_ext_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t msg_add_ext_text(char * buf, size_t size, const char * text, size_t text_len, unsigned char endc)
```

```json
{
  "name": "msg_add_ext_text",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580614514,
      "name": "msg_add_ext_text",
      "external": false,
      "loc": "kernel/printk/printk.c:645",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:msg_add_dict_text"
      ],
      "caller_func": [
        "kernel/printk/printk.c:printk_get_next_message",
        "kernel/printk/printk.c:msg_add_dict_text",
        "kernel/printk/printk.c:msg_add_dict_text"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580607104,
      "name": "msg_add_ext_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
ssize_t msg_add_ext_text(char * buf, size_t size, const char * text, size_t text_len, unsigned char endc)
```
</details>
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
