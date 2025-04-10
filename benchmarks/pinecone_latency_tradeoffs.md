# Pinecone Latency Tradeoffs

## Key Findings
- Best performance with `s1` pod type
- Query latency < 100ms with < 1M vectors
- Cost scales linearly with number of pods

## Tips
- Use metadata filtering to reduce scope
- Batch upserts to minimize IOPS cost
