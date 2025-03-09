# Function: <code>get_free_page_and_send</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585184153,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:581",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
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
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585396327,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:572",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
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
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585536647,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:576",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
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
int get_free_page_and_send(struct virtio_balloon * vb)
```

```json
{
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586249168,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:629",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586249168,
      "name": "get_free_page_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
int get_free_page_and_send(struct virtio_balloon * vb)
```

```json
{
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586367440,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:621",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586367440,
      "name": "get_free_page_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586257365,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:621",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
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
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586767941,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:621",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
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
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588039955,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:621",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
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
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589418321,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:614",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
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
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589717521,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:614",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
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
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590055169,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:653",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
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
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498193260,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:576",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
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
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230955672,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:576",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
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
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291433316,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:576",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
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
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275972958,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:576",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
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
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585298679,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:576",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
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
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585251191,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:576",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
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
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585487047,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:576",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
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
  "name": "get_free_page_and_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585591111,
      "name": "get_free_page_and_send",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:576",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
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
int get_free_page_and_send(struct virtio_balloon * vb)
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
int get_free_page_and_send(struct virtio_balloon * vb)
```
</details>
</li>
</ul>
