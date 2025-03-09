# Function: <code>bio_first_folio</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_first_folio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583597764,
      "name": "bio_first_folio",
      "external": false,
      "loc": "include/linux/bio.h:277",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
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
  "name": "bio_first_folio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584203588,
      "name": "bio_first_folio",
      "external": false,
      "loc": "include/linux/bio.h:277",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
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
  "name": "bio_first_folio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584146277,
      "name": "bio_first_folio",
      "external": false,
      "loc": "include/linux/bio.h:279",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_write_end_io",
        "fs/mpage.c:mpage_write_end_io",
        "fs/mpage.c:mpage_read_end_io",
        "fs/mpage.c:mpage_read_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584327077,
      "name": "bio_first_folio",
      "external": false,
      "loc": "include/linux/bio.h:279",
      "file": "fs/crypto/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/bio.c:fscrypt_decrypt_bio",
        "fs/crypto/bio.c:fscrypt_decrypt_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584343575,
      "name": "bio_first_folio",
      "external": false,
      "loc": "include/linux/bio.h:279",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584433489,
      "name": "bio_first_folio",
      "external": false,
      "loc": "include/linux/bio.h:279",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584979813,
      "name": "bio_first_folio",
      "external": false,
      "loc": "include/linux/bio.h:279",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584985109,
      "name": "bio_first_folio",
      "external": false,
      "loc": "include/linux/bio.h:279",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:__read_end_io",
        "fs/ext4/readpage.c:__read_end_io"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bio_first_folio(struct folio_iter * fi, struct bio * bio, int i)
```

```json
{
  "name": "bio_first_folio",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bio_first_folio",
      "external": false,
      "loc": "include/linux/bio.h:284",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:mpage_write_end_io",
        "fs/mpage.c:mpage_write_end_io",
        "fs/mpage.c:mpage_read_end_io",
        "fs/mpage.c:mpage_read_end_io"
      ]
    },
    {
      "addr": 0,
      "name": "bio_first_folio",
      "external": false,
      "loc": "include/linux/bio.h:284",
      "file": "fs/crypto/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_decrypt_bio",
        "fs/crypto/bio.c:fscrypt_decrypt_bio"
      ]
    },
    {
      "addr": 18446744071584562296,
      "name": "bio_first_folio",
      "external": false,
      "loc": "include/linux/bio.h:284",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:fsverity_verify_bio"
      ],
      "caller_func": [
        "fs/verity/verify.c:fsverity_verify_bio"
      ]
    },
    {
      "addr": 18446744071584655134,
      "name": "bio_first_folio",
      "external": false,
      "loc": "include/linux/bio.h:284",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585211632,
      "name": "bio_first_folio",
      "external": false,
      "loc": "include/linux/bio.h:284",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    },
    {
      "addr": 18446744071585217188,
      "name": "bio_first_folio",
      "external": false,
      "loc": "include/linux/bio.h:284",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:__read_end_io"
      ],
      "caller_func": [
        "fs/ext4/readpage.c:__read_end_io"
      ]
    },
    {
      "addr": 0,
      "name": "bio_first_folio",
      "external": false,
      "loc": "include/linux/bio.h:284",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_set_pages_dirty",
        "block/bio.c:bio_set_pages_dirty",
        "block/bio.c:__bio_release_pages",
        "block/bio.c:__bio_release_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584362000,
      "name": "bio_first_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071597481085,
      "name": "bio_first_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584542800,
      "name": "bio_first_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071597486287,
      "name": "bio_first_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584558896,
      "name": "bio_first_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071597487538,
      "name": "bio_first_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071585210640,
      "name": "bio_first_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071597510064,
      "name": "bio_first_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071585216560,
      "name": "bio_first_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071597510654,
      "name": "bio_first_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071586884464,
      "name": "bio_first_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071597534380,
      "name": "bio_first_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void bio_first_folio(struct folio_iter * fi, struct bio * bio, int i)
```
</details>
</li>
</ul>
