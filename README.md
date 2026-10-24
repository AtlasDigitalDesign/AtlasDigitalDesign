## Jeff Combs, growth engineer

I build and run the technical side of online stores. The storefront, the structured data search
engines read, the product feeds, the analytics that count correctly, the paid campaigns on top of
them, and the imagery that sells the product. Denver, Colorado.

Most of what I ship lives inside a client's business, so this account holds the pieces I can show.

**[atlas-shopify-toolkit](https://github.com/AtlasDigitalDesign/atlas-shopify-toolkit)**
Selected code from a production Shopify store. Product and collection JSON-LD for a product type
schema.org has no vocabulary for, a replacement Pinterest catalog feed written in Liquid, a sitewide
repricing tool that captures its own rollback file before it writes anything, and the allocation
core of a revenue-split app that reconciles to the cent.

**[atlasofplantbased-mcp](https://github.com/AtlasDigitalDesign/atlasofplantbased-mcp)**
A read-only MCP server for Pacific Crest Trail data. Twenty-six legs by trail mile, towns, passes
and lakes, and vegan resupply at 64 stops with last-checked dates. The dataset is also on
[Hugging Face](https://huggingface.co/datasets/AtlasDigitalDesign/pct-vegan-resupply).

### How I work

I build with AI coding agents against a spec I hold, and I verify the result against the live
system before I call it done. Every change on a client store is proposed before it is made, checked
after it ships, and logged with a rollback.

The verification is the job. A regression suite I wrote against a frozen baseline caught a defect in
my own parser that had been dropping base prices out of bundled orders, a five-figure understatement
across fifty orders. A strict XML parse of a product feed I rebuilt surfaced four defects that every
browser renders without complaining. I keep a record of the defects I find, and my own are in it.

Case study with sourced figures: [atlasdigital.design/work/intertwine](https://atlasdigital.design/work/intertwine/)

atlasdigital.design · [LinkedIn](https://www.linkedin.com/in/jeff-combs-atlas) · jeff@atlasdigital.design
