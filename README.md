# Kehai Companion: recommended models

The list of language models Kehai Companion offers when it is set up, read by the app from
`models.json` here so it can change without a new release. Each entry:

- `tag`: what Ollama downloads (a library name, or `hf.co/<repo>:<quant>`)
- `name`, `by`, `description`: how it is shown
- `sizeGb`: download size; `needsGb`: video memory to run it fully on the GPU
- `sees` / `hears`: takes images / sound; `uncensored`: uncensored or abliterated, else the maker's standard model
- `settings`: app settings the model needs

Every model listed must be able to see images (screen vision depends on it).
