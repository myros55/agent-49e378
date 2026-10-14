# Poppins agent template

Aeon (https://github.com/aeonfun/aeon.git) at upstream commit `19cdf2b0f7e1ce87375898411e493110fa8fac20`, with these changes:

- removed .github/workflows/ci-aeon-skill-sync.yml
- removed .github/workflows/ci-agents-md.yml
- removed .github/workflows/ci-apps.yml
- removed .github/workflows/ci-capabilities-parity.yml
- removed .github/workflows/ci-gate.yml
- removed .github/workflows/ci-harness-cli.yml
- removed .github/workflows/ci-harnesses-json.yml
- removed .github/workflows/ci-packs-json.yml
- removed .github/workflows/ci-readme-catalog.yml
- removed .github/workflows/ci-shellcheck.yml
- removed .github/workflows/ci-skill-category.yml
- removed .github/workflows/ci-skill-integrity.yml
- removed .github/workflows/ci-skill-packs.yml
- removed .github/workflows/ci-skills-json.yml
- removed .github/workflows/ci-tests.yml
- removed the cron trigger from scheduler.yml
- removed the cron trigger from messages.yml
- removed the push trigger from setup-commands.yml
- added MiniRouter model routing to scripts/llm-gateway.sh
- default model zai/glm-5.3-flash

Runs are dispatched by the Poppins backend when skills are due; nothing here runs on a timer.
