# Function: <code>config_item_cleanup</code>

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
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581867136,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:149",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_put"
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
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582017109,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:149",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_release"
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
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582205509,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:149",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_release"
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
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582300517,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:133",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_release"
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
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582466853,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:119",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_release"
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
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582565797,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:119",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_release"
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
void config_item_cleanup(struct config_item * item)
```

```json
{
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582874000,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:119",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582874000,
      "name": "config_item_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
void config_item_cleanup(struct config_item * item)
```

```json
{
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582946864,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:119",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582946864,
      "name": "config_item_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
void config_item_cleanup(struct config_item * item)
```

```json
{
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582974352,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:117",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974352,
      "name": "config_item_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
void config_item_cleanup(struct config_item * item)
```

```json
{
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583309952,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:117",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583309952,
      "name": "config_item_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
void config_item_cleanup(struct config_item * item)
```

```json
{
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583817136,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:117",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583817136,
      "name": "config_item_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void config_item_cleanup(struct config_item * item)
```

```json
{
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584439088,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:117",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584439088,
      "name": "config_item_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void config_item_cleanup(struct config_item * item)
```

```json
{
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584667856,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:117",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584667856,
      "name": "config_item_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void config_item_cleanup(struct config_item * item)
```

```json
{
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584900624,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:117",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584900624,
      "name": "config_item_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494211332,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:119",
      "file": "fs/configfs/item.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227642772,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:119",
      "file": "fs/configfs/item.c",
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
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287905504,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:119",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_put"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void config_item_cleanup(struct config_item * item)
```

```json
{
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273669624,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:119",
      "file": "fs/configfs/item.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/item.c:config_item_cleanup",
        "fs/configfs/item.c:config_item_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273669624,
      "name": "config_item_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582534533,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:119",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_release"
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
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582471701,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:119",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_release"
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
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582525013,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:119",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_release"
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
  "name": "config_item_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582605685,
      "name": "config_item_cleanup",
      "external": false,
      "loc": "fs/configfs/item.c:119",
      "file": "fs/configfs/item.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/item.c:config_item_release"
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
void config_item_cleanup(struct config_item * item)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void config_item_cleanup(struct config_item * item)
```
</details>
</li>
</ul>
