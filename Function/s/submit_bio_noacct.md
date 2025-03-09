# Function: <code>submit_bio_noacct</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
blk_qc_t submit_bio_noacct(struct bio * bio)
```

```json
{
  "name": "submit_bio_noacct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584487840,
      "name": "submit_bio_noacct",
      "external": true,
      "loc": "block/blk-core.c:1044",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:__blk_queue_split",
        "block/bounce.c:__blk_queue_bounce",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-crypto-fallback.c:blk_crypto_split_bio_if_needed",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584487840,
      "name": "submit_bio_noacct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
blk_qc_t submit_bio_noacct(struct bio * bio)
```

```json
{
  "name": "submit_bio_noacct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584522080,
      "name": "submit_bio_noacct",
      "external": true,
      "loc": "block/blk-core.c:1030",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "drivers/md/md.c:md_submit_discard_bio",
        "drivers/md/md.c:md_submit_discard_bio",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584522080,
      "name": "submit_bio_noacct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
blk_qc_t submit_bio_noacct(struct bio * bio)
```

```json
{
  "name": "submit_bio_noacct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584929792,
      "name": "submit_bio_noacct",
      "external": true,
      "loc": "block/blk-core.c:1019",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "drivers/md/md.c:md_submit_discard_bio",
        "drivers/md/md.c:md_submit_discard_bio",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584929792,
      "name": "submit_bio_noacct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void submit_bio_noacct(struct bio * bio)
```

```json
{
  "name": "submit_bio_noacct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "submit_bio_noacct",
      "external": true,
      "loc": "block/blk-core.c:756",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "drivers/md/md.c:md_submit_discard_bio",
        "drivers/md/md.c:md_submit_discard_bio",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:dm_submit_bio_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594095605,
      "name": "submit_bio_noacct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071585633120,
      "name": "submit_bio_noacct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void submit_bio_noacct(struct bio * bio)
```

```json
{
  "name": "submit_bio_noacct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "submit_bio_noacct",
      "external": true,
      "loc": "block/blk-core.c:722",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-merge.c:__bio_split_to_limits",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "drivers/md/md.c:md_submit_discard_bio",
        "drivers/md/md.c:md_submit_discard_bio",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:dm_submit_bio_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596104779,
      "name": "submit_bio_noacct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071586404320,
      "name": "submit_bio_noacct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1434
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void submit_bio_noacct(struct bio * bio)
```

```json
{
  "name": "submit_bio_noacct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "submit_bio_noacct",
      "external": true,
      "loc": "block/blk-core.c:720",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:__bio_split_to_limits",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "drivers/md/md.c:md_submit_discard_bio",
        "drivers/md/md.c:md_submit_discard_bio",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:dm_submit_bio_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596628707,
      "name": "submit_bio_noacct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071586651536,
      "name": "submit_bio_noacct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1499
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
void submit_bio_noacct(struct bio * bio)
```

```json
{
  "name": "submit_bio_noacct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "submit_bio_noacct",
      "external": true,
      "loc": "block/blk-core.c:730",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:__bio_split_to_limits",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "drivers/md/md.c:md_submit_discard_bio",
        "drivers/md/md.c:md_submit_discard_bio",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:dm_submit_bio_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597534926,
      "name": "submit_bio_noacct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071586922704,
      "name": "submit_bio_noacct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1441
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
blk_qc_t submit_bio_noacct(struct bio * bio)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>blk_qc_t</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
