# Function: <code>cfq_rb_erase</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cfq_rb_erase",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582897990,
      "name": "cfq_rb_erase",
      "external": false,
      "loc": "block/cfq-iosched.c:1197",
      "file": "block/cfq-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_group_service_tree_del",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_del_cfqq_rr"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cfq_rb_erase",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583199257,
      "name": "cfq_rb_erase",
      "external": false,
      "loc": "block/cfq-iosched.c:1220",
      "file": "block/cfq-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_group_service_tree_del"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cfq_rb_erase",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583297238,
      "name": "cfq_rb_erase",
      "external": false,
      "loc": "block/cfq-iosched.c:1211",
      "file": "block/cfq-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_group_service_tree_del"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cfq_rb_erase",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583359570,
      "name": "cfq_rb_erase",
      "external": false,
      "loc": "block/cfq-iosched.c:1207",
      "file": "block/cfq-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_group_service_tree_del"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void cfq_rb_erase(struct rb_node * n, struct cfq_rb_root * root)
```

```json
{
  "name": "cfq_rb_erase",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583540768,
      "name": "cfq_rb_erase",
      "external": false,
      "loc": "block/cfq-iosched.c:1183",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_group_service_tree_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583540768,
      "name": "cfq_rb_erase",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void cfq_rb_erase(struct rb_node * n, struct cfq_rb_root * root)
```

```json
{
  "name": "cfq_rb_erase",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583756240,
      "name": "cfq_rb_erase",
      "external": false,
      "loc": "block/cfq-iosched.c:1186",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_group_service_tree_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583756240,
      "name": "cfq_rb_erase",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void cfq_rb_erase(struct rb_node * n, struct cfq_rb_root * root)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void cfq_rb_erase(struct rb_node * n, struct cfq_rb_root * root)
```
</details>
</li>
</ul>
