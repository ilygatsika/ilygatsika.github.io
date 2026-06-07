## Footprint

Size of the generated HTML on disk
    zola build
    du -sh public

Transferred size over the network in bytes
    zola serve
    lighthouse http://127.0.0.1:1026/ --output=json --quiet | jq '.audits["total-byte-weight"].numericValue'
