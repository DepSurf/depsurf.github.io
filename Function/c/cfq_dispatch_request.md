# Function: <code>cfq_dispatch_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cfq_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582920470,
      "name": "cfq_dispatch_request",
      "external": false,
      "loc": "block/cfq-iosched.c:3465",
      "file": "block/cfq-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_dispatch_requests"
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
  "name": "cfq_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583208185,
      "name": "cfq_dispatch_request",
      "external": false,
      "loc": "block/cfq-iosched.c:3508",
      "file": "block/cfq-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_dispatch_requests"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool cfq_dispatch_request(struct cfq_data * cfqd, struct cfq_queue * cfqq)
```

```json
{
  "name": "cfq_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583313520,
      "name": "cfq_dispatch_request",
      "external": false,
      "loc": "block/cfq-iosched.c:3502",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_dispatch_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583313520,
      "name": "cfq_dispatch_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 759
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool cfq_dispatch_request(struct cfq_data * cfqd, struct cfq_queue * cfqq)
```

```json
{
  "name": "cfq_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583375456,
      "name": "cfq_dispatch_request",
      "external": false,
      "loc": "block/cfq-iosched.c:3509",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_dispatch_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583375456,
      "name": "cfq_dispatch_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cfq_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583559460,
      "name": "cfq_dispatch_request",
      "external": false,
      "loc": "block/cfq-iosched.c:3486",
      "file": "block/cfq-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_dispatch_requests"
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
  "name": "cfq_dispatch_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583772150,
      "name": "cfq_dispatch_request",
      "external": false,
      "loc": "block/cfq-iosched.c:3489",
      "file": "block/cfq-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_dispatch_requests"
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool cfq_dispatch_request(struct cfq_data * cfqd, struct cfq_queue * cfqq)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
bool cfq_dispatch_request(struct cfq_data * cfqd, struct cfq_queue * cfqq)
```
</details>
</li>
</ul>
