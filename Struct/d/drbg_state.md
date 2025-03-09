# Struct: <code>drbg_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * ctr_null_value_buf;
    __u8 * ctr_null_value;
    struct completion ctr_completion;
    int ctr_async_err;
    bool seeded;
    bool pr;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * ctr_null_value_buf;
    __u8 * ctr_null_value;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct completion ctr_completion;
    int ctr_async_err;
    bool seeded;
    bool pr;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * ctr_null_value_buf;
    __u8 * ctr_null_value;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct completion ctr_completion;
    int ctr_async_err;
    bool seeded;
    bool pr;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * ctr_null_value_buf;
    __u8 * ctr_null_value;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    bool seeded;
    bool pr;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * ctr_null_value_buf;
    __u8 * ctr_null_value;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    bool seeded;
    bool pr;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    bool seeded;
    bool pr;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    bool seeded;
    bool pr;
    bool fips_primed;
    unsigned char * prev;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    bool seeded;
    bool pr;
    bool fips_primed;
    unsigned char * prev;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    bool seeded;
    bool pr;
    bool fips_primed;
    unsigned char * prev;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    bool seeded;
    bool pr;
    bool fips_primed;
    unsigned char * prev;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    bool seeded;
    bool pr;
    bool fips_primed;
    unsigned char * prev;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    bool seeded;
    bool pr;
    bool fips_primed;
    unsigned char * prev;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    enum drbg_seed_state seeded;
    long unsigned int last_seed_time;
    bool pr;
    bool fips_primed;
    unsigned char * prev;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    enum drbg_seed_state seeded;
    long unsigned int last_seed_time;
    bool pr;
    bool fips_primed;
    unsigned char * prev;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    enum drbg_seed_state seeded;
    long unsigned int last_seed_time;
    bool pr;
    bool fips_primed;
    unsigned char * prev;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    enum drbg_seed_state seeded;
    long unsigned int last_seed_time;
    bool pr;
    bool fips_primed;
    unsigned char * prev;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    bool seeded;
    bool pr;
    bool fips_primed;
    unsigned char * prev;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    bool seeded;
    bool pr;
    bool fips_primed;
    unsigned char * prev;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    bool seeded;
    bool pr;
    bool fips_primed;
    unsigned char * prev;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    bool seeded;
    bool pr;
    bool fips_primed;
    unsigned char * prev;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    bool seeded;
    bool pr;
    bool fips_primed;
    unsigned char * prev;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    bool seeded;
    bool pr;
    bool fips_primed;
    unsigned char * prev;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    bool seeded;
    bool pr;
    bool fips_primed;
    unsigned char * prev;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * outscratchpadbuf;
    __u8 * outscratchpad;
    struct crypto_wait ctr_wait;
    struct scatterlist sg_in;
    struct scatterlist sg_out;
    bool seeded;
    bool pr;
    bool fips_primed;
    unsigned char * prev;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct drbg_state {
    struct mutex drbg_mutex;
    unsigned char * V;
    unsigned char * Vbuf;
    unsigned char * C;
    unsigned char * Cbuf;
    size_t reseed_ctr;
    size_t reseed_threshold;
    unsigned char * scratchpad;
    unsigned char * scratchpadbuf;
    void * priv_data;
    struct crypto_skcipher * ctr_handle;
    struct skcipher_request * ctr_req;
    __u8 * ctr_null_value_buf;
    __u8 * ctr_null_value;
    struct completion ctr_completion;
    int ctr_async_err;
    bool seeded;
    bool pr;
    struct work_struct seed_work;
    struct crypto_rng * jent;
    const struct drbg_state_ops * d_ops;
    const struct drbg_core * core;
    struct drbg_string test_data;
    struct random_ready_callback random_ready;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u8 * outscratchpadbuf</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 * outscratchpad</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct crypto_wait ctr_wait</code>
</li>
<li>
<b>Field removed. </b>
<code>struct completion ctr_completion</code>
</li>
<li>
<b>Field removed. </b>
<code>int ctr_async_err</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct scatterlist sg_in</code>
</li>
<li>
<b>Field added. </b>
<code>struct scatterlist sg_out</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 * ctr_null_value_buf</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 * ctr_null_value</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool fips_primed</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char * prev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int last_seed_time</code>
</li>
<li>
<b>Field removed. </b>
<code>struct work_struct seed_work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct random_ready_callback random_ready</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool seeded</code> ➡️ <code>enum drbg_seed_state seeded</code>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
