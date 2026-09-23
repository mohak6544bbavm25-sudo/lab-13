Executive Summary & Academic Overview
This laboratory exercise demonstrates the practical application, evaluation, and verification of Retrieval-Augmented Generation (RAG) within an aviation management context. Utilizing a fictional AeroVista Airlines Baggage Policy as an anchor document, the study evaluates how document-grounded AI architectures enhance information accuracy and operational reliability compared to baseline parametric language models.

The activity examines the fundamental dual-phase mechanism of RAG—comprising targeted semantic retrieval followed by context-bounded generation. Through comparative auditing, the investigation illustrates the primary failure modes of ungrounded models, notably their tendency to invent precise reporting procedures, specific reimbursement figures, and binding delivery timelines. Conversely, when constrained by explicit system prompts ("Use only the uploaded document..."), the RAG framework restricts generated outputs to verified source text, enforcing transparency through section-level citations and standardizing explicit declarations ("Not found in the supplied document") whenever information gaps occur.

To safeguard operational integrity, the lab establishes a structured Five-Step Verification Routine:

Claim Extraction: Identifying discrete factual assertions within generated responses.

Source Mapping: Locating corresponding passages in authoritative documents.

Claim–Source Match Verification: Confirming strict alignment between assertions and underlying text.

Context Retention Audit: Ensuring crucial conditional logic, policy exceptions, and modal qualifiers (e.g., may, subject to) remain intact.

Action Determination: Formally accepting, correcting, or escalating outputs to authorized personnel.

A comprehensive risk audit further highlights systemic vulnerabilities inherent to RAG deployments, including outdated source repositories, retrieval mismatches, and citation halluncinations—where authoritative-looking references are paired with inaccurate text. Ultimately, this exercise underscores that while RAG significantly improves factual grounding, enterprise implementation requires human-in-the-loop oversight. In safety-critical and customer-facing domains like aviation, AI outputs must remain secondary tools for operational research, with final authority retained by human management.
