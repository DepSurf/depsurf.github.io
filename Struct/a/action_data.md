# Struct: <code>action_data</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct action_data {
    action_fn_t fn;
    unsigned int n_params;
    char *[16] params;
    struct (anon) onmatch;
    struct (anon) onmax;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct action_data {
    action_fn_t fn;
    unsigned int n_params;
    char *[16] params;
    struct (anon) onmatch;
    struct (anon) onmax;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct action_data {
    enum handler_id handler;
    enum action_id action;
    char * action_name;
    action_fn_t fn;
    unsigned int n_params;
    char *[16] params;
    unsigned int var_ref_idx;
    struct synth_event * synth_event;
    bool use_trace_keyword;
    char * synth_event_name;
    struct (anon) match_data;
    struct (anon) track_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct action_data {
    enum handler_id handler;
    enum action_id action;
    char * action_name;
    action_fn_t fn;
    unsigned int n_params;
    char *[16] params;
    unsigned int[16] var_ref_idx;
    struct synth_event * synth_event;
    bool use_trace_keyword;
    char * synth_event_name;
    struct (anon) match_data;
    struct (anon) track_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct action_data {
    enum handler_id handler;
    enum action_id action;
    char * action_name;
    action_fn_t fn;
    unsigned int n_params;
    char *[32] params;
    unsigned int[16] var_ref_idx;
    struct synth_event * synth_event;
    bool use_trace_keyword;
    char * synth_event_name;
    struct (anon) match_data;
    struct (anon) track_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct action_data {
    enum handler_id handler;
    enum action_id action;
    char * action_name;
    action_fn_t fn;
    unsigned int n_params;
    char *[32] params;
    unsigned int[16] var_ref_idx;
    struct synth_event * synth_event;
    bool use_trace_keyword;
    char * synth_event_name;
    struct (anon) match_data;
    struct (anon) track_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct action_data {
    enum handler_id handler;
    enum action_id action;
    char * action_name;
    action_fn_t fn;
    unsigned int n_params;
    char *[32] params;
    unsigned int[16] var_ref_idx;
    struct synth_event * synth_event;
    bool use_trace_keyword;
    char * synth_event_name;
    struct (anon) match_data;
    struct (anon) track_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct action_data {
    enum handler_id handler;
    enum action_id action;
    char * action_name;
    action_fn_t fn;
    unsigned int n_params;
    char *[64] params;
    unsigned int[16] var_ref_idx;
    struct synth_event * synth_event;
    bool use_trace_keyword;
    char * synth_event_name;
    struct (anon) match_data;
    struct (anon) track_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct action_data {
    enum handler_id handler;
    enum action_id action;
    char * action_name;
    action_fn_t fn;
    unsigned int n_params;
    char *[64] params;
    unsigned int[16] var_ref_idx;
    struct synth_event * synth_event;
    bool use_trace_keyword;
    char * synth_event_name;
    struct (anon) match_data;
    struct (anon) track_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct action_data {
    enum handler_id handler;
    enum action_id action;
    char * action_name;
    action_fn_t fn;
    unsigned int n_params;
    char *[64] params;
    unsigned int[64] var_ref_idx;
    struct synth_event * synth_event;
    bool use_trace_keyword;
    char * synth_event_name;
    struct (anon) match_data;
    struct (anon) track_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct action_data {
    enum handler_id handler;
    enum action_id action;
    char * action_name;
    action_fn_t fn;
    unsigned int n_params;
    char *[64] params;
    unsigned int[64] var_ref_idx;
    struct synth_event * synth_event;
    bool use_trace_keyword;
    char * synth_event_name;
    struct (anon) match_data;
    struct (anon) track_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct action_data {
    enum handler_id handler;
    enum action_id action;
    char * action_name;
    action_fn_t fn;
    unsigned int n_params;
    char *[64] params;
    unsigned int[64] var_ref_idx;
    struct synth_event * synth_event;
    bool use_trace_keyword;
    char * synth_event_name;
    struct (anon) match_data;
    struct (anon) track_data;
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
struct action_data {
    enum handler_id handler;
    enum action_id action;
    char * action_name;
    action_fn_t fn;
    unsigned int n_params;
    char *[16] params;
    unsigned int[16] var_ref_idx;
    struct synth_event * synth_event;
    bool use_trace_keyword;
    char * synth_event_name;
    struct (anon) match_data;
    struct (anon) track_data;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct action_data {
    enum handler_id handler;
    enum action_id action;
    char * action_name;
    action_fn_t fn;
    unsigned int n_params;
    char *[16] params;
    unsigned int[16] var_ref_idx;
    struct synth_event * synth_event;
    bool use_trace_keyword;
    char * synth_event_name;
    struct (anon) match_data;
    struct (anon) track_data;
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct action_data {
    enum handler_id handler;
    enum action_id action;
    char * action_name;
    action_fn_t fn;
    unsigned int n_params;
    char *[16] params;
    unsigned int[16] var_ref_idx;
    struct synth_event * synth_event;
    bool use_trace_keyword;
    char * synth_event_name;
    struct (anon) match_data;
    struct (anon) track_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct action_data {
    enum handler_id handler;
    enum action_id action;
    char * action_name;
    action_fn_t fn;
    unsigned int n_params;
    char *[16] params;
    unsigned int[16] var_ref_idx;
    struct synth_event * synth_event;
    bool use_trace_keyword;
    char * synth_event_name;
    struct (anon) match_data;
    struct (anon) track_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct action_data {
    enum handler_id handler;
    enum action_id action;
    char * action_name;
    action_fn_t fn;
    unsigned int n_params;
    char *[16] params;
    unsigned int[16] var_ref_idx;
    struct synth_event * synth_event;
    bool use_trace_keyword;
    char * synth_event_name;
    struct (anon) match_data;
    struct (anon) track_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct action_data {
    enum handler_id handler;
    enum action_id action;
    char * action_name;
    action_fn_t fn;
    unsigned int n_params;
    char *[16] params;
    unsigned int[16] var_ref_idx;
    struct synth_event * synth_event;
    bool use_trace_keyword;
    char * synth_event_name;
    struct (anon) match_data;
    struct (anon) track_data;
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct action_data {
    action_fn_t fn;
    unsigned int n_params;
    char *[16] params;
    struct (anon) onmatch;
    struct (anon) onmax;
}
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum handler_id handler</code>
</li>
<li>
<b>Field added. </b>
<code>enum action_id action</code>
</li>
<li>
<b>Field added. </b>
<code>char * action_name</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int var_ref_idx</code>
</li>
<li>
<b>Field added. </b>
<code>struct synth_event * synth_event</code>
</li>
<li>
<b>Field added. </b>
<code>bool use_trace_keyword</code>
</li>
<li>
<b>Field added. </b>
<code>char * synth_event_name</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) match_data</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) track_data</code>
</li>
<li>
<b>Field removed. </b>
<code>struct (anon) onmatch</code>
</li>
<li>
<b>Field removed. </b>
<code>struct (anon) onmax</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>unsigned int var_ref_idx</code> ➡️ <code>unsigned int[16] var_ref_idx</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>char *[16] params</code> ➡️ <code>char *[32] params</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>char *[32] params</code> ➡️ <code>char *[64] params</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>unsigned int[16] var_ref_idx</code> ➡️ <code>unsigned int[64] var_ref_idx</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct action_data {
    enum handler_id handler;
    enum action_id action;
    char * action_name;
    action_fn_t fn;
    unsigned int n_params;
    char *[16] params;
    unsigned int[16] var_ref_idx;
    struct synth_event * synth_event;
    bool use_trace_keyword;
    char * synth_event_name;
    struct (anon) match_data;
    struct (anon) track_data;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct action_data {
    enum handler_id handler;
    enum action_id action;
    char * action_name;
    action_fn_t fn;
    unsigned int n_params;
    char *[16] params;
    unsigned int[16] var_ref_idx;
    struct synth_event * synth_event;
    bool use_trace_keyword;
    char * synth_event_name;
    struct (anon) match_data;
    struct (anon) track_data;
}
```
</details>
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
