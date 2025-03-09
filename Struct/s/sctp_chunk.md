# Struct: <code>sctp_chunk</code>

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
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 pmtu_probe;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 pmtu_probe;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 pmtu_probe;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 pmtu_probe;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 pmtu_probe;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
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
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
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
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
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
struct sctp_chunk {
    struct list_head list;
    refcount_t refcnt;
    int sent_count;
    struct list_head transmitted_list;
    struct list_head stream_list;
    struct list_head frag_list;
    struct sk_buff * skb;
    struct sk_buff * head_skb;
    struct sctp_shared_key * shkey;
    union sctp_params param_hdr;
    union (anon) subh;
    __u8 * chunk_end;
    struct sctp_chunkhdr * chunk_hdr;
    struct sctphdr * sctp_hdr;
    struct sctp_sndrcvinfo sinfo;
    struct sctp_association * asoc;
    struct sctp_ep_common * rcvr;
    long unsigned int sent_at;
    union sctp_addr source;
    union sctp_addr dest;
    struct sctp_datamsg * msg;
    struct sctp_transport * transport;
    struct sk_buff * auth_chunk;
    __u16 rtt_in_progress;
    __u16 has_tsn;
    __u16 has_ssn;
    __u16 singleton;
    __u16 end_of_packet;
    __u16 ecn_ce_done;
    __u16 pdiscard;
    __u16 tsn_gap_acked;
    __u16 data_accepted;
    __u16 auth;
    __u16 has_asconf;
    __u16 tsn_missing_report;
    __u16 fast_retransmit;
}
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u16 pmtu_probe</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
