# Function: <code>nvm_register_map</code>

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
  "name": "nvm_register_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584978754,
      "name": "nvm_register_map",
      "external": false,
      "loc": "drivers/lightnvm/core.c:385",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_register"
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
  "name": "nvm_register_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585399982,
      "name": "nvm_register_map",
      "external": false,
      "loc": "drivers/lightnvm/core.c:406",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_register"
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
  "name": "nvm_register_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585637971,
      "name": "nvm_register_map",
      "external": false,
      "loc": "drivers/lightnvm/core.c:498",
      "file": "drivers/lightnvm/core.c",
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
  "name": "nvm_register_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585767293,
      "name": "nvm_register_map",
      "external": false,
      "loc": "drivers/lightnvm/core.c:503",
      "file": "drivers/lightnvm/core.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvm_register_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585999629,
      "name": "nvm_register_map",
      "external": false,
      "loc": "drivers/lightnvm/core.c:505",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_register"
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
  "name": "nvm_register_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586146797,
      "name": "nvm_register_map",
      "external": false,
      "loc": "drivers/lightnvm/core.c:510",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_register"
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
int nvm_register_map(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586903616,
      "name": "nvm_register_map",
      "external": false,
      "loc": "drivers/lightnvm/core.c:509",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586903616,
      "name": "nvm_register_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
int nvm_register_map(struct nvm_dev * dev)
```

```json
{
  "name": "nvm_register_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586988480,
      "name": "nvm_register_map",
      "external": false,
      "loc": "drivers/lightnvm/core.c:505",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586988480,
      "name": "nvm_register_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
  "name": "nvm_register_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586874071,
      "name": "nvm_register_map",
      "external": false,
      "loc": "drivers/lightnvm/core.c:505",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_init"
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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "nvm_register_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498939704,
      "name": "nvm_register_map",
      "external": false,
      "loc": "drivers/lightnvm/core.c:510",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_register"
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
  "name": "nvm_register_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231511300,
      "name": "nvm_register_map",
      "external": false,
      "loc": "drivers/lightnvm/core.c:510",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_register"
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
  "name": "nvm_register_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292076424,
      "name": "nvm_register_map",
      "external": false,
      "loc": "drivers/lightnvm/core.c:510",
      "file": "drivers/lightnvm/core.c",
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
  "name": "nvm_register_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276324544,
      "name": "nvm_register_map",
      "external": false,
      "loc": "drivers/lightnvm/core.c:510",
      "file": "drivers/lightnvm/core.c",
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
  "name": "nvm_register_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585907165,
      "name": "nvm_register_map",
      "external": false,
      "loc": "drivers/lightnvm/core.c:510",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_register"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvm_register_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586096813,
      "name": "nvm_register_map",
      "external": false,
      "loc": "drivers/lightnvm/core.c:510",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_register"
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
  "name": "nvm_register_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586205421,
      "name": "nvm_register_map",
      "external": false,
      "loc": "drivers/lightnvm/core.c:510",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_register"
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
int nvm_register_map(struct nvm_dev * dev)
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
int nvm_register_map(struct nvm_dev * dev)
```
</details>
</li>
</ul>
