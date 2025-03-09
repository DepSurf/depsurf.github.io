# Function: <code>bsg_set_command_q</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bsg_set_command_q",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584015515,
      "name": "bsg_set_command_q",
      "external": false,
      "loc": "block/bsg.c:332",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_ioctl"
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
  "name": "bsg_set_command_q",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584119035,
      "name": "bsg_set_command_q",
      "external": false,
      "loc": "block/bsg.c:332",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_ioctl"
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
int bsg_set_command_q(struct bsg_device * bd, int * uarg)
```

```json
{
  "name": "bsg_set_command_q",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584515312,
      "name": "bsg_set_command_q",
      "external": false,
      "loc": "block/bsg.c:332",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584515312,
      "name": "bsg_set_command_q",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int bsg_set_command_q(struct bsg_device * bd, int * uarg)
```

```json
{
  "name": "bsg_set_command_q",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584624176,
      "name": "bsg_set_command_q",
      "external": false,
      "loc": "block/bsg.c:334",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584624176,
      "name": "bsg_set_command_q",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int bsg_set_command_q(struct bsg_device * bd, int * uarg)
```

```json
{
  "name": "bsg_set_command_q",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584652384,
      "name": "bsg_set_command_q",
      "external": false,
      "loc": "block/bsg.c:334",
      "file": "block/bsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584652384,
      "name": "bsg_set_command_q",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
  "name": "bsg_set_command_q",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585068668,
      "name": "bsg_set_command_q",
      "external": false,
      "loc": "block/bsg.c:90",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_ioctl"
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
  "name": "bsg_set_command_q",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585793641,
      "name": "bsg_set_command_q",
      "external": false,
      "loc": "block/bsg.c:90",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_ioctl"
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
  "name": "bsg_set_command_q",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586574713,
      "name": "bsg_set_command_q",
      "external": false,
      "loc": "block/bsg.c:90",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_ioctl"
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
  "name": "bsg_set_command_q",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586832526,
      "name": "bsg_set_command_q",
      "external": false,
      "loc": "block/bsg.c:92",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_ioctl"
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
  "name": "bsg_set_command_q",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587109646,
      "name": "bsg_set_command_q",
      "external": false,
      "loc": "block/bsg.c:92",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_ioctl"
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
  "name": "bsg_set_command_q",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495965224,
      "name": "bsg_set_command_q",
      "external": false,
      "loc": "block/bsg.c:332",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_ioctl"
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
  "name": "bsg_set_command_q",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229307224,
      "name": "bsg_set_command_q",
      "external": false,
      "loc": "block/bsg.c:332",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_ioctl"
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
  "name": "bsg_set_command_q",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290185352,
      "name": "bsg_set_command_q",
      "external": false,
      "loc": "block/bsg.c:332",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_ioctl"
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
  "name": "bsg_set_command_q",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275068228,
      "name": "bsg_set_command_q",
      "external": false,
      "loc": "block/bsg.c:332",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_ioctl"
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
  "name": "bsg_set_command_q",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584087771,
      "name": "bsg_set_command_q",
      "external": false,
      "loc": "block/bsg.c:332",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_ioctl"
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
  "name": "bsg_set_command_q",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584023531,
      "name": "bsg_set_command_q",
      "external": false,
      "loc": "block/bsg.c:332",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_ioctl"
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
  "name": "bsg_set_command_q",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584071531,
      "name": "bsg_set_command_q",
      "external": false,
      "loc": "block/bsg.c:332",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_ioctl"
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
  "name": "bsg_set_command_q",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584174107,
      "name": "bsg_set_command_q",
      "external": false,
      "loc": "block/bsg.c:332",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_ioctl"
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
int bsg_set_command_q(struct bsg_device * bd, int * uarg)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int bsg_set_command_q(struct bsg_device * bd, int * uarg)
```
</details>
</li>
</ul>
