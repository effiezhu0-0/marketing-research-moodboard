# Output Schema

`manifest.json` records project metadata, standard URL/extraction date, platform visits, query families, evidence track, project-anchor use, adaptation reason, queries, login status, feedback/design-case/observation/rejection counts, limitations, asset paths, source/image URLs, and dimensions. Every counted feedback item and social-platform design case also records `detail_url`, `screenshot_path`, `capture_type` (`element`, `stitched`, or `full_page`), and `capture_coverage` flags for platform context, author/account, full relevant text, evidence-bearing media, visible date, and relevant comments.

`data.json` records brief, carriers, standards, feedback, design cases, observations, rejected candidates with reasons, baselines, insights, attributions, maturity, provisional/approved directions, positive references, negative examples, judgments, and provenance. Feedback and design-case rows preserve the screenshot asset and the exact quote/fact, interpretation, project implication, source, date, engagement signals when visible, and confidence shown beside it.

Leave unknown values empty. Never guess dates, authors, metrics, URLs, or dimensions.
