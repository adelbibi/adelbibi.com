---
title: "The Alignment Curse: Modality Alignment Supercharges Audio Attacks via Text Transfer"

# Authors
authors:
- Yupeng Chen
- Junchi Yu
- Aoxi Liu
- Baoyuan Wu
- Philip Torr
- admin

# Author notes (optional)
author_notes:
- ""
- ""
- ""
- ""
- ""
- ""

date: "2026-09-24"
doi: ""

publishDate: "2026-09-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Neural Information Processing Systems (**NeurIPS26**)
publication_short: Neural Information Processing Systems (**NeurIPS26**)

abstract: "Recent advances in end-to-end trained omni-models have substantially improved audio capabilities by strengthening text-audio modality alignment. However, whether such alignment inadvertently facilitates the transfer of safety vulnerabilities across modalities remains underexplored. This question is critical as text-based jailbreak attacks are considerably more mature than audio-based ones; if they transfer systematically, current audio safety evaluations may underestimate risks originating from the text modality. In this paper, we introduce the Alignment Curse, a formally characterized and empirically validated principle showing that stronger modality alignment enables more effective transfer of attacks from text to audio, revealing a fundamental tension between capability and safety. Motivated by this principle, we conduct a comprehensive black-box evaluation of three attack categories on recent omni-models (e.g., Qwen2.5-Omni, Qwen3-Omni): text attacks, text-transferred audio attacks, and audio attacks. We find that text-transferred audio attacks perform comparably to, and often better than, audio-based attacks, exhibiting a clear advantage under audio-only access. This suggests that text-based vulnerabilities play a pivotal role in shaping audio safety risks. Finally, we empirically analyze the relationship between modality alignment and transfer effectiveness across attack methods and models, observing consistent support for the Alignment Curse: tighter modality alignment leads to more effective cross-modality attack transfer."

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2602.02557'
url_code: 'https://github.com/Samchen2003/Alignment_Curse_Release'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

projects: []
slides: ''
---
