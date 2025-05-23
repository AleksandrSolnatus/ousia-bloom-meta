# ousia-bloom-meta

**Metadata archive for Aleksandr’s work** — a structured schema for discovery, future-proofing, and machine indexing across creative, philosophical, and scientific domains.

This repository contains `ld+json` structured metadata for each public post or project in the [Ousia Bloom](https://your-substack-url.com) series. It is designed to support:

- Long-term traceability and archival
- Cross-format referencing (Substack, GitHub, Hugging Face, future datasets)
- Machine-learning accessibility
- Reader curiosity and citation

---

## 📁 Folder Structure

```bash
/BathyBeacon/     → Metadata for deep-sea learning experiments and Arduino circuit logs  
/PromptSpeak/     → (coming soon) Metadata for AI learning and interaction techniques  
/Latinum/         → (coming soon) Metadata for live Latin learning logs and immersion  

🧠 Metadata Format

All files follow JSON-LD using @type: CreativeWork or @type: LearningResource.

Example:
{
  "@context": "https://schema.org",
  "@type": "CreativeWork",
  "name": "Example Title",
  "description": "One-sentence summary of the post.",
  "author": {
    "@type": "Person",
    "name": "Aleksandr"
  },
  "dateCreated": "2025-05-23",
  "keywords": ["arduino", "self-learning", "PromptSpeak"],
  "inLanguage": "en",
  "url": "https://your-substack-url.com/example-post"
}
