# Function: <code>__bio_iov_append_get_pages</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __bio_iov_append_get_pages(struct bio * bio, struct iov_iter * iter)
```

```json
{
  "name": "__bio_iov_append_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584347776,
      "name": "__bio_iov_append_get_pages",
      "external": false,
      "loc": "block/bio.c:1036",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584347776,
      "name": "__bio_iov_append_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
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
int __bio_iov_append_get_pages(struct bio * bio, struct iov_iter * iter)
```

```json
{
  "name": "__bio_iov_append_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584464528,
      "name": "__bio_iov_append_get_pages",
      "external": false,
      "loc": "block/bio.c:1036",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584464528,
      "name": "__bio_iov_append_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
  "name": "__bio_iov_append_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584499478,
      "name": "__bio_iov_append_get_pages",
      "external": false,
      "loc": "block/bio.c:1037",
      "file": "block/bio.c",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __bio_iov_append_get_pages(struct bio * bio, struct iov_iter * iter)
```

```json
{
  "name": "__bio_iov_append_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bio_iov_append_get_pages",
      "external": false,
      "loc": "block/bio.c:1130",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584909840,
      "name": "__bio_iov_append_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
    },
    {
      "addr": 18446744071592312744,
      "name": "__bio_iov_append_get_pages.cold",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __bio_iov_append_get_pages(struct bio * bio, struct iov_iter * iter)
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
int __bio_iov_append_get_pages(struct bio * bio, struct iov_iter * iter)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int __bio_iov_append_get_pages(struct bio * bio, struct iov_iter * iter)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int __bio_iov_append_get_pages(struct bio * bio, struct iov_iter * iter)
```
</details>
</li>
</ul>
