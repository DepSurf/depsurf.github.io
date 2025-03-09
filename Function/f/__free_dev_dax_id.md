# Function: <code>__free_dev_dax_id</code>

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
  "name": "__free_dev_dax_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587449877,
      "name": "__free_dev_dax_id",
      "external": false,
      "loc": "drivers/dax/bus.c:407",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/dax/bus.c:delete_store"
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
  "name": "__free_dev_dax_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587331553,
      "name": "__free_dev_dax_id",
      "external": false,
      "loc": "drivers/dax/bus.c:408",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/dax/bus.c:delete_store"
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
  "name": "__free_dev_dax_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587898379,
      "name": "__free_dev_dax_id",
      "external": false,
      "loc": "drivers/dax/bus.c:406",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/dax/bus.c:delete_store"
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
  "name": "__free_dev_dax_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589247993,
      "name": "__free_dev_dax_id",
      "external": false,
      "loc": "drivers/dax/bus.c:436",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/dax/bus.c:delete_store"
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
  "name": "__free_dev_dax_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590807530,
      "name": "__free_dev_dax_id",
      "external": false,
      "loc": "drivers/dax/bus.c:436",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/dax/bus.c:delete_store"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int __free_dev_dax_id(struct dev_dax * dev_dax)
```

```json
{
  "name": "__free_dev_dax_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__free_dev_dax_id",
      "external": false,
      "loc": "drivers/dax/bus.c:463",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/dax/bus.c:delete_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591142496,
      "name": "__free_dev_dax_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071596786839,
      "name": "__free_dev_dax_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int __free_dev_dax_id(struct dev_dax * dev_dax)
```

```json
{
  "name": "__free_dev_dax_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__free_dev_dax_id",
      "external": false,
      "loc": "drivers/dax/bus.c:464",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/dax/bus.c:delete_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591487536,
      "name": "__free_dev_dax_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071597695774,
      "name": "__free_dev_dax_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int __free_dev_dax_id(struct dev_dax * dev_dax)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
