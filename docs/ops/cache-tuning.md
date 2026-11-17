# Cache tuning (operations)

Segment time-to-live is controlled by `cache.ttl_seconds`. Lower values reclaim
memory faster at the cost of more re-fetches. Purge behaviour is reviewed every
release; see the pending documentation entries checklist for open items.
