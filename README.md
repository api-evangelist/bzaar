# Bzaar

Bzaar is a cross-border business-to-business wholesale marketplace founded in 2020-2021 by Nishant Verman (previously head of corporate development at Flipkart) and Prasanth Nair (previously engineering and product at Amazon, Flipkart, and Lazada), headquartered in Palo Alto / San Francisco, California with operations in India. The platform connected small and medium retailers in the United States and other markets with curated suppliers and manufacturers in India and Southeast Asia across home, lifestyle, accessories, apparel, jewelry, cookware, and bakeware verticals, layering vendor management, quality control, consolidated logistics, and cross-border payments on top of the catalog.

Bzaar raised a $4 million seed round led by Canaan Partners, with participation from Binny Bansal, Sameer Nigam, Rahul Chari, Lee Fixel, and Ashish Gupta.

Backed by: canaan-partners

## API surface

As of the 2026-07-20 enrichment pass, Bzaar publishes **no public API surface**: no developer portal, API documentation, API reference, OpenAPI/AsyncAPI specification, SDK packages on any public registry, GitHub organization, or `/.well-known/` discovery documents.

`bzaar.com` returns an identical GoDaddy parking-lander document on every path (a verified soft-404), so the web product is not live — though the domain remains actively owned, running Google Workspace mail with SPF and a `p=quarantine` DMARC policy.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| Domain security | `security/bzaar-domain-security.yml` | probed |
| Well-known probe (0 documents) | `well-known/bzaar-well-known.yml` | probed |
