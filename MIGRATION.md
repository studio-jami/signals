# Migration Guide - Populate All Your Task History

## Quick Bulk Setup (Run this)

```bash
git pull

# Creates full taxonomy from your screenshot + common ones
mkdir -p signals/{divr,huntr,signl,build,api}/{models,multimodal,build,primitives,insights,world-models,avatars,voice} 

# Example population
cat > "signals/divr/models/divr-models-06-22-2026.md" << 'EOL'
# PASTE FULL OUTPUT FROM YOUR TASK HISTORY HERE
EOL

git add signals/ && git commit -m "chore: bulk dirs for all tasks" && git push
```

Drop **every** result from the last weeks into the matching folder using the naming rule.

I will commit anything you paste directly into the repo instantly.

**List the main task types** you have results for (or paste one big block) and I’ll generate the exact files + commit them right now.