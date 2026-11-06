# Nature Skills installation

Source: https://github.com/Yuan1z0825/nature-skills
Pinned upstream commit: d774add241c65e89ed17a4da573b472b0972fd42
License: Apache-2.0; see LICENSE in this directory and any bundled asset licenses.

The complete upstream skills/ tree is installed under .agents/skills/, including
nature-shared and all reference documents, scripts, templates, images and PDFs.
The installer verifies all 818 file blob hashes and executable modes across
24 skill directories before committing them.

Open a new Codex task with this repository selected after merging the pull
request. For example: "Use nature-polishing to polish this paragraph."

Python packages, browser runtimes, API credentials and MCP services are not
installed by copying the skill files. Configure these only as needed for a task.
The installation workflow is pinned to the upstream commit above; it does not
automatically update from upstream.
