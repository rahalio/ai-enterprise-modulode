# Modulode — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### Data scientist

- As a data scientist, I want to upload a trained artifact and publish an endpoint in one guided flow, so that I spend time on models rather than containers.
- As a data scientist, I want the platform to select the smallest package set for my framework, so that cold starts stay acceptable.
- As a data scientist, I want to test-invoke before publish, so that I do not break downstream apps with a bad build.

### ML platform admin

- As a platform admin, I want to register new package sets for emerging frameworks, so that teams are not blocked waiting for a mega-image rebuild.
- As a platform admin, I want version bumps to be forced when someone changes network or ownership settings, so that “config tweaks” cannot silently break pipelines.
- As a platform admin, I want to retire a non-compliant version with an audit reason, so that we meet regulatory obligations without deleting history.

### Application developer

- As an application developer, I want stable SDK snippets to call a specific model version, so that my service does not float to whatever was published last.
- As an application developer, I want older versions to keep answering while I plan an upgrade, so that model teams’ velocity does not dictate my release train.

### ML engineer / pipeline owner

- As an ML engineer, I want to chain models from different frameworks into a versioned pipeline, so that OCR-to-sentiment style workflows are first-class products.
- As an ML engineer, I want pipeline failures to name the step and model version, so that debugging does not require guessing.

### FinOps / platform owner

- As a FinOps analyst, I want inference and storage cost attributed by model version and consumer, so that mega-image waste and orphan versions are visible.
- As a platform owner, I want a report of data-scientist time spent on deployment vs. modeling proxies (publish lead time, failed dep builds), so that I can prove the 75/25 inversion is reversing.
- As a security officer, I want callability and network-access changes flagged as major versions, so that permission drift is reviewable.
