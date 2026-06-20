'''# Create the skill directory
mkdir -p ~/.hermes/skills/note-taking/vault-evolve

# Copy the file there
cp SKILL.md ~/.hermes/skills/note-taking/vault-evolve/SKILL.md

# Set your vault path (if not already set)
echo 'OBSIDIAN_VAULT_PATH=/your/actual/vault/path' >> ~/.hermes/.env

# Verify Hermes sees it
hermes skills list | grep vault-evolve'''
