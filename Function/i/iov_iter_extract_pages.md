# Function: <code>iov_iter_extract_pages</code>

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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t iov_iter_extract_pages(struct iov_iter * i, struct page * * * pages, size_t maxsize, unsigned int maxpages, iov_iter_extraction_t extraction_flags, size_t * offset0)
```

```json
{
  "name": "iov_iter_extract_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iov_iter_extract_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1819",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_direct_IO",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/blk-map.c:bio_map_user_iov",
        "net/core/skbuff.c:skb_splice_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596640237,
      "name": "iov_iter_extract_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071587316880,
      "name": "iov_iter_extract_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1199
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
ssize_t iov_iter_extract_pages(struct iov_iter * i, struct page * * * pages, size_t maxsize, unsigned int maxpages, iov_iter_extraction_t extraction_flags, size_t * offset0)
```

```json
{
  "name": "iov_iter_extract_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iov_iter_extract_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1632",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_direct_IO",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/blk-map.c:bio_map_user_iov",
        "block/bio-integrity.c:bio_integrity_map_user",
        "block/bio-integrity.c:bio_integrity_map_user",
        "net/core/skbuff.c:skb_splice_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597548417,
      "name": "iov_iter_extract_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071587599504,
      "name": "iov_iter_extract_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1329
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
ssize_t iov_iter_extract_pages(struct iov_iter * i, struct page * * * pages, size_t maxsize, unsigned int maxpages, iov_iter_extraction_t extraction_flags, size_t * offset0)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
